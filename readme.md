Download ActiveMQ using below link :
https://activemq.apache.org/components/classic/download/

Starting ActiveMQ Server :
------------------------------------------------------------------------------
    i) open CMD and point the bin directory of ActiveMQ Installation Folder.
    ii) run "activemq start" command.
    iii) then ActiveMQ Server Starts.
  
Launching The Application 
----------------------------------------------------------------------------------------------
    run both Consumer and Producer Programs by giving any of the below as Program Arguments.
        1) topic - For Implementing Publisher and Subscriber Communication
        2) queue - For Implementing Point to Point Communication.
        3) if producer sends "shutdown" message both Producer and Consumer will stop running.
