
# Operating system1


## 1. what is  operating system?

- 執行用戶程式並讓用戶問題解決上變簡單
- 讓電腦變得更加容易使用
- 在一個有效的方法下使用硬體

## 2. computer system divided into four component
- (1) hareware -ex : CPU, memory, I/O devices
- (2) operating system -ex : Controls and coordinates use of hardware among various applications and users
- (3) applicaion program -ex :Word processors, compilers, web browsers, database systems, video games
- (4) user -ex : People, machines, other computers

## 3. component relation ship
![](https://i.imgur.com/fvLbzin.png =600x)

## 4. kernel
- kernel就是系統上面的一個檔案， 這個檔案包含了驅動主機各項硬體的偵測程式與驅動模組

## 5. bus(匯流排)
- I/O設備透過bus來連接跟分享記憶體

## 6.interrupt
- interrupt vector contains the address of all service routines
- Trap or Exception is a software-generated interrupt caused either by an error or a user request
- An operating system is interrupt driven
## 7. main memory and other memory
- random access
- volatile
- DRAM
- secondary storage
    - nonvolatile -> NVM
- device controller transfers blocks of data from buffer storage directly to main memory without CPU intervention -> DMA
 
- main memory can be viewed as a cache for secondary storage


![](https://i.imgur.com/u9mDNnK.png =700x)

## 8. Dual mode
- User mode & kernel mode
- mode bit -> Provides ability to distinguish when system is running user code or kernel code

## 9. Timer 
- set to interrupt the computer after period
- keep a counter that is decremented by the physical clock

## 10. Multiprocessors(parallel systems)
- 優點
    - 1. Increased throughput
    - 2. Economy of scale
    - 3. Increased reliability 
- two types
    - 1. Asymmetric Multiprocessing -> each processor is assigned a specie task
    - 2. Symmetric Multiprocessing  -> each processor performs all tasks

## 11. mobile 
- more OS features(GPS...)
- use IEEE802.11 wireless for connectivity
- P2P
    - 不分client和server