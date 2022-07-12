# AI-BASED-CHATBOT-FOR-INDUSTRIAL-PROCESS-MONITORING-FOR-PAPERCUTTING-MACHINE
For industry 4.0 to provide way to create a truly objective measures of production and enhance industries performance.

Many companies dedicate specific employees to monitor their production lines, since problems can occur at virtually any point in manufacturing, that might leave operator or manufacturer guessing from where certain defects or delays originate which gives a limited view of what is going on in one place at a given time, thus monitors the process flow and fix malfunctions or faults in not real-time way and hence lead to inefficiency industrial performance.

This problem associates with the manual monitoring approach where the operator should be present physically around the machine to sets parameter and oversee the operation state of the machine from the start of production, through different manufacturing stages, and all the way to final inspection. This has courage’s to the development of industrial process monitoring system that will offer remote control and monitoring of the machine and its process. So instructions and parameter setting to machine will be provide from this system and feedback about the operation faults and current states will be present. Provision of command instructions and getting feedbacks through the system in real time way is like conversation between the operator providing instructions and the monitoring system providing state feedback, hence AI based chatbot (conversational agent) is proposed and developed to be industrial process monitoring system from the early method of being almost around machine where now through this chatbot will monitor machine remotely while being in a single position unless on the time of resolving detected faults.

# SOFTWARE IMPLEMENTATION.
## A. ENVIRONMENT SETUP AND INSTALLATIONS.

In software implementation, there is a need to install 

1. IDE software where codes are written from. The choosen IDE is VS code, visual studio code, since it offers many powerfull extensions. For VScode installations see https://code.visualstudio.com/download

2. Installing Git for the given operating system to have version control sytem. Git installation provides Bash (Bourne-again shell), which is the same commandprocessor that the Unix systems use. Bash is much more powerful than the defaultWindows command line, For Git installations see https://git-scm.com/download/win.

3. Installing python to the machine so we can download libraries(packages) from other programmers through using pip command. These installed libraries extend the functionality of the standard Python library. For python installation to machine see https://www.python.org/downloads/

Then after installations of the above, then is setting up of virtual environment to support the implementation of the algroithm. Open the VScode, from bash terminal write down the below commands:

4. Virtual environment setup
    
   ```
     $ cd chatbot-develop
     $ python -m venv venv
     $ . venv/Scripts/activate
   ```

Where "chatbot-develop" is the folder name for the project.

5. Installations of packages

   `  $ pip install Flask torch torchvision nltk cors `

## B. CLONE AND TRAINING

6. Clone this repository from the bash terminal to the "chatbot-develop" by writting:
    
    ` $ git clone https://github.com/CnQzdr/AI-BASED-CHATBOT-FOR-INDUSTRIAL-PROCESS-MONITORING-FOR-PAPERCUTTING-MACHINE/tree/main/Chatbot-develop `

7. To train an algorthm
     
   `  $ python training.py `

8. Start conversation
    
    ` $ python main.py `

# HARDWARE IMPLEMENTATION

## A. COMPONENTS
The hardware system that will control the machine through the developed chatbot needs:

1. Motors(stepper motors). They suite well for accurate positioning and repeatability, and speed control.

2. Motor drivers(A4988). They provide microstepping for intermediate steps.

3. AC Transformer. To stepdown 240V/60Hz.

4. Wi-Fi module(ESP32 WROOM).

5. RELAY.

## B. HARDWARE DESIGN AND CODE IDE

1. Simulation software(Proteus 8 Professional). For Proteus installation see https://www.labcenter.com/

2. Embedded Code IDE(Arduino IDE). For Arduino IDE installation see https://www.arduino.cc/en/software

Schematic design and PCB layout are provided in "Hardware-develop" folder from this repository.
