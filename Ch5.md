# Operating system 5

## 1. CPU scheduling
- CPU burst followed I/O burst
- dispatch latency
    - time it takes for the dispatcher to stop one process and start another running

## 2. FCFS
- AVG time = all waiting time/amount of process
- convoy effect
    - short process behind long process

## 3. SJF(optimal)
- how to determine the len of next CPU burst
    - ask user 
    - estimate
- the short the process is , the order of it will in the head
- $α$ set
 ![](https://i.imgur.com/zApi2kl.png)
 
## 4. Shortest-remaining-time-first
- 剩下時間最少的先做,若來的process處理時間小於目前process剩餘處理時間則先做
![](https://i.imgur.com/LOrFVU9.png)


## 5. RR(round robin)
- divide time in q
- q = 3
 ![](https://i.imgur.com/HyZoDX6.png)

## 6. RR with priority
- process with same priority use RR
- q = 2
![](https://i.imgur.com/Qe723Cg.png)
