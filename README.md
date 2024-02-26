# agentic_framework


Notes

1) api key variable needs to be set
2) You can change the mode as ALWAYS or NEVER to switch between automatic or human input (In the below code)
   user_proxy = IPythonUserProxyAgent( name = "user_proxy", 
    system_message="Your act as the user. Your task is to get work done. Please ensure you return the desired output. Do not return a blank output.",
                            code_execution_config={"work_dir": "coding", 
                                                   "use_docker": False,
                                                    },
                               max_consecutive_auto_reply=100,
                           human_input_mode="ALWAYS",llm_config=llm_config)

   3) pip install pyautogen
      (https://microsoft.github.io/autogen/)
