####test
*You may wish to consider generating a graph to show your project workflow. GitHub markdown provides native support for [mermaid](https://mermaid.js.org/syntax/flowchart.html), an example of which is provided below:*


```mermaid
flowchart LR
    
        direction TB
        code_input1[(trade data submitted)]
        code_input2[(trade data not submitted)]
    

  subgraph common_utility
       direction LR
       Workflow[clean column names]
       rename_variables
       add_index_number 
       add_year 
       direction LR
       Workflow[clean column names2]
       rename_variables2
       add_index_number2
       add_year2

    end
    
   

code_input1 --> common_utility
code_input2 --> common_utility



  



