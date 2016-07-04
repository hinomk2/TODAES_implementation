# TODAES_implementation
usage : java -jar TODAES_submission.jar xmlPath
        ex) java -jar TODAES_submission.jar output.xml
        
In xml file, task id 0 is the TIDG graph. other tasks should consist of one subtask, which is a independent real-time task.
Subtask-to-PE mapping is described in PE_list/PE.
dependency element describes the dependency edges in the TIDG graph.
