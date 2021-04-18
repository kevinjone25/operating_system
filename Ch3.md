# Operating System 3

## 1. Process
- programe code ->text section
- current activity including program counter
- Stack containing temporary data -> like return address ,local var, function parameter
- Data section inckuding global var
- Heap containing memory dynamically allocated in runtime(ex in c: buffer = (char*) malloc (i+1))
- program is==passive== stored in disk, but proces is ==active==
![](https://i.imgur.com/fPgLICg.png =400x)

## 2.Process state
![](https://i.imgur.com/u0xrAb1.png)

## 3. PCB(Process Control block)
- process state
- program counter
- CPU register
- CPU scheduling information
- memory-menegement information
- accounting information
- I/O status information


## 4. Context switch
- when CPU switch to another process, system save the state of the old process and load saved state for new  porcess
- context store in PCB

## 5. Processs creation
- parent create child process ,from a tree
- process can managed through pid(process identifier)
- fork() and wait()
- abort() is used when 
    - child has exceed allocated resource
    - task assigned to child is no longer required
    - parent is exiting , and OS must let clild terminated
![](https://i.imgur.com/oTazHAq.png)

- zombie 
    - no parent wainting
- orphan
    - parent terminated without invoking orphon
 
 ## 6. Race condition
 - when thread use same var in same time the result of except may be changed
 - to avoid the race condition,use the 
 - IPC 
     - let process communicate to each other 
     - bi-directional
## 7. Socket
- defined as an endpoint for communication
- contain three things
    - IP address
    - transport protocol
    - port number