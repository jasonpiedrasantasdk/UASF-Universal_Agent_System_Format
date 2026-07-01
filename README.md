# UASF - Universal Agent System Format
###### *Previously Named - (MoE-AC)Mastery-of-Expert-Agent-Creation*

this repository serves as a sharepoint for my workflow in creating Universal Agents. This workflow (previously called MoE Agents aka 'Mastery Of Expert Agent Creation'), is ideal for creating agents for a targeted Model Providor or for any Model Provider. The workflow is quite simple and infact provides a near perfect end product for one shot instructions. you may have to cut off the changelog or request the model producing
the instructions to provide a leaner output with the following prompt:

**"Export copy ready portion of output file only. do not include changelog"**

please be sure to use this responsibly.

## How to use:

### Option A(Recommended for Claude):

**Skill (Claude Desktop / claude.ai — no subscription tier required):**

1. Download [`skills/uasf-agent-architect/SKILL.md`](skills/uasf-agent-architect/SKILL.md) from this repo, or package the folder yourself into a `.skill` file
2. Claude Desktop / claude.ai → Settings → Capabilities → Skills → Upload
3. Enable it

Once uploaded, just ask Claude to build/convert/upgrade an agent spec — it auto-triggers off intent, no slash command needed.

**Claude Code Plugin (CLI or Desktop Code tab):**

Add Git Repo to the Claude Marketplace Custom Plugins Claude Code:
```
/plugin marketplace add jasonpiedrasantasdk/UASF-Universal_Agent_System_Format
```
Then Install the plugin and reload with:
```
/plugin install uasf-agent-architect
/reload-plugins
```
In the Claude Code tab or CLI use:
```
/project-instruction-uasf
```

### OR:
For Claude Destkop: 

NAVIGATE TO: Customize >> Personal Plugins >> Add >> Add Marketplace >> Add From Repository >> jasonpiedrasantasdk/UASF-Universal_Agent_System_Format

##### Install The Skill File

Download Repo from Github or use: 
```
git clone https://github.com/jasonpiedrasantasdk/UASF-Universal_Agent_System_Format.git
```

NAVIGATE TO: Customize >> Personal Plugin >> Add >> Upload >> /Path/To/Git/Repo/

Then add the skill:
NAVIGATE TO: Customize >> Skills >> Add >> Upload Skill >> /Path/To/Git/Repo/skills/uasf-agent-architect/uasf-agent-architect.skill
Then use the skill with:
```
/uasf-agent-architect 
```

After you complete the installation you can either directly ask claude to generate an agent and say 'use the uasf-agent-architect' with your requirements. Or you create a prompt in another LLM to get the specifics down for what you want generated, and then inject the same phrase with your prompt to generate an agent.

### Option B:

1. Choose 2 Model Providers(1 is ssufficient but 2 is recommended), one for synthesis of your Input Injection Prompt. The Second for the Agent Generation.(I chose Gemini and Claude)

  ###### A. I chose Gemini 3.X Pro For the best Contextual Language
  ###### B. I chose Claude Opus 4.X, however Model Sonnet 5 is sufficient

2. Have a nice conversation with your model A to generate a prompt for your Agent, noting the specific language and important characteristics you wish to estabish for your agent. At this time you should specify the Endpoint or what platform you are creating the agent for. In most cases UASF will generate a Universal Agent. If you dont specify the model agent then you will get a universal agent. Only by adding the model you intend the agent to work with will you get tailored phrasing and instruction.

###### *NOTE: It is strongly recommended to create a single prompt with a model in mind and then when you need to use it for another, simply ask your B Model to make a copy tailored to the Secondary Model Provider. However, as this is a Universal Builder, Its not strictly required.*

3. Once Satisfied witht the Prompt from Model A, go to the Model B and include the 'Project_Instruction_UASF_Agent_Architect_v1.md' as an attached file and sumbit your prompt.

At this point the model should generate a complete and UASF Formatted Agent File. Use this for the Provider of your choice.

---

### Example Files:

##### *[Mistral_Studio_Agent - Research+Development](Mistral_Studio_Agent%20-%20Research+Development.md)* 
##### *[Mistral_Studio_Agent - Chef_Mistral](Mistral_Studio_Agent-Chef_Mistral.yaml)* 
##### *[Mistral_Studio_Agent - CopyCopy_Mistral_LeLawyer](Mistral_Studio_Agent%20-%20CopyCopy_Mistral_LeLawyer.yaml)* 
##### *[Mistral_Studio_Agent - Doc_Mistral_MD](Mistral_Studio_Agent%20-%20Doc_Mistral_MD.yaml)* 

***

### Future Updates:

##### 1. Script setup with 4B Model for full suite creation
##### 2. GUI with Logging and Agent Portfolio for Suite
