# JudiciarySystem-Dapp-React-Ethereum
Introduction : A Smart Contract Blockchain system focusing on the Judiciary system with 3 main actors.
1.       Civilian
2.       Lawyer
3.       Judge Process
-----------------------------------
Features:
1.       Civilians appeal for a case by adding a case and giving a fee\
2.       Lawyers then choose a case from the list of cases as they see fit 
3.       A part of case fee amount is given to Lawyer 
4.       Lawyer may choose to be the defendant or the persecutor of the particular case 
5.       Lawyer also submits related evidence/proof according to the case 
6.       After this, the case is transferred to a Judge 
7.       Judge may choose if the case appeal is successful/True or unsuccessful/False 
8.       If the Civilian wins the case then the fee is refunded to the Civilian otherwise complete fee is now non refundable 
9.       All the steps are handled using the smart contract 
-----------------------------------


-----------------------------------
Smart Contract Functions:
           listCases
          Lists all the registered cases.
           setJudge
           Sets the Judge for the Case
           setLawyer
           Lawyer can also be set
           addCase
           Civilians add cases using this function
           setDefenderCase
           If lawyer is defender for a case
           setProsecutorCase
           If lawyer is prosecutor for a case
           addDefenderProof
           Lawyer adds Proof as defender
           addProsecutorProof
           Lawyer adds Proof as Prosecutor
           decision
           Only judge adds the decision if true than money is returned to plaintiff

Execution requirements:
1.       React
2.       npm install materialize-css@next
3.       Ganache
4.       Truffle

Execution Steps:
Turn on  Ganache QuickStart workspace
Run truffle migrate on “ProjectIBC” folder
Run Truffle console in this folder
Now move to JudApp in “ProjectIBC” folder
Now “npm install” in JudApp folder
Now npm install materialize-css@next
After this “npm start” to run react app

