# UASF - Universal Agent System Format
###### *Previously Named - (MoE-AC)Mastery-of-Expert-Agent-Creation*

this repository serves as a sharepoint for my workflow in creating speacialized agents
which i decided to also call MoE Agents aka 'Mastery Of Expert Agent Creation'. The workflow is quite simple and infact provides a near perfect end product for one shot instructions. you may have to cut off the changelog or request the model producing
the instructions to provide a leaner output with the following prompt:

**"Export copy ready portion of output file only. do not include changelog"**

please be sure to use this responsibly.

## How to use:

1. Choose 2 Model Providers(1 is ssufficient but 2 is recommended), one for synthesis of your Input Injection Prompt. The Second for the Agent Generation.(I chose Gemini and Claude)

  ###### A. I chose Gemini 3.1 Pro For the best Contextual Language
  ###### B. I chose Claude Opus 4.6, however Model Sonnet 4.6 is sufficient

2. Have a nice conversation with your model A to generate a prompt for your Agent, noting the specific language and important characteristics you wish to estabish for your agent. At this time you should specify the Endpoint or what platform you are creating the agent for. In most cases UASF will generate a Universal Agent. If you dont specify the model agent then you will get a universal agent. Only by adding the model you intend the agent to work with will you get tailored phrasing and instruction.

###### *NOTE: It is strongly recommended to create a single prompt with a model in mind and then when you need to use it for another, simply ask your B Model to make a copy tailored to the Secondary Model Provider. However, as this is a Universal Builder, Its not strictly required.*

3. Once Satisfied witht the Prompt from Model A, go to the Model B and include the 'Project_Instruction_UASF_Agent_Architect_v1.md' as an attached file and sumbit your prompt.

At this point the model should generate a complete and UASF Formatted Agent File. Use this for the Provider of your choice.

----------------------------------------------------------------------------

### Example Files:

##### *Mistral_Studio_Agent - Research+Development* 
##### *Mistral_Studio_Agent - Chef_Mistral* 
##### *Mistral_Studio_Agent - CopyCopy_Mistral_LeLawyer* 
##### *Mistral_Studio_Agent - Doc_Mistral_MD* 

