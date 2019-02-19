# Home loan Mortgage Approval System

<img src="clips/static/hdb-bto.png"
     style="float: left; margin-right: 0px;" />

### Credits
### Project members of Institute of Systems Science, National University of Singapore:
* Ong Boon Ping

---

### [ 1 ] To run the program using iss-vm

download pre-built virtual machine from http://bit.ly/iss-vm

start iss-vm

open terminal in iss-vm

$ git clone https://github.com/optimusium/trial

Getting zip file. Unzip the zip file.

Create any space. Run 
file:///home/iss-user/trial/Mortgage_Process_ISS_MR

---

### [ 2 ] Changes
Changing reasoning rules into rdrl files.

Changing ruleflow-group to mortgagemachinereasoningDT2
using new rdrl file to insert fact based on ownHouse and hasJob.

File mortgagemachinereasoningDT2 consists of guided rule where ownHouse and hasJob equal to 0.

File mortgagemachinereasoningDT1 consists of guided rule where ownHouse or hasJob equal to 1.

---

### [ 3 ] Features

In rule task “Mortgage Machine Reasoning DT”, changing rule flow group to mortgagemachinereasoningDT2.

<img src="https://github.com/optimusium/trial/blob/master/ProcessDiagram.png"
     style="float: left; margin-right: 0px;" />
<img src="https://github.com/optimusium/trial/blob/master/RuleFlowGroup.png"
     style="float: left; margin-right: 0px;" />
Using 2 guided rule files with same ruleflow-group to replace the decision table. (it can also be accomplished using 1 rdrl file but want to try whether using 2 rule files is workable. Moreover, 1 guided rule file can only cater 1 rule.)

<img src="https://github.com/optimusium/trial/blob/master/DT1_rule.png"
     style="float: left; margin-right: 0px;" />
<img src="https://github.com/optimusium/trial/blob/master/DT2_rule.png"
     style="float: left; margin-right: 0px;" />



