[Personal Learning Record](../../personal_learning_record/personal_learning_record.md) | [Session Notes](../sessions/README.md) 

# Session 5

## Topics covered
*What topics were covered in this session*

Java script

C code

subroutines and stacks

Interrupts


## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*

Standard library that is part of the c liner that can be used when writing code on Java script

Loads up address of 'Hello World'
C langauge is compiled into machine code
Bytes can be read by the CPU
Assembly code responds as bites and bytes

ARM chips has three registers that are called stack pointer, link register, and the program counter

Program counter points to the next instruction to the memeory

<img width="515" height="242" alt="image" src="https://github.com/user-attachments/assets/3a10f58e-c311-4a7b-8109-bf4aba8f6bf1" />

Figure 1 (Anon. n.d.) - Sub routine and stacks

Ths stack has two specfic functuins in which are PUSH and POP in which one adds onto the stack and one removes something from the stack

Link register is going to point to the next instruction in the previous sub routine and that means you can jump back to the program counter, in summary it acts as a save

Stack pointer is a sophisticated way to stack the routine and take it back to the CPU register

Stack has two purposes which is push and pop and usually goes into a sub routine being able to store information from the processor back to the stack

Load register 4 into 1
bl means branch
lr means link register

An interrupt is a 'signal emmitted by a device attached to a computer or from a program within the computer. It requires the OS to stop and figure out what to do next'. Overseen at, (Awati 2022) 

Interrupts in summary is where a keybaord interrupts the process of whatever the CPU is doing, it enabled through an interrupts controller

There is a clock every time it clocks there will be an interrupt

GPIo pins could be an interrupt

It corresponds to the programs memory

A driver is a program where the interrupt will jump to then to the CPU

The interrupt takes whatever its doing and puts it into the stack, if there are multiple interrupts where subroutines are simultaneously happening.

Certain programs cant be interrupted, therefore, there is protected parts of certain programs

two loops withan an assembler working through strings, loading in the value and then it wirte that strings out to then jump back

Seven segment displays having 7 leds in which can be created into numerical values
## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*
<img width="2166" height="506" alt="image" src="https://github.com/user-attachments/assets/5370ae3f-fc50-4a18-abe7-4a390966480e" />

This is writing both segments of displays to 0, I must see which segments will give me 1,2,3,4

loading into register 0 and I have to put the binary number into the seven segment display to give me a 1, therefore it will write 1 into a value

Each of the value corresponds to different value

## Summary of learning
*What did you learn through these exercises*

Through this excercise I learnt how to change the seven elements upon numerical value, replacing 0000000, to 123456.

References

ANON., n.d. Subroutines and Stacks Available from: https://www.scs.stanford.edu/~zyedidia/docs/arm/extras/annot/subroutines.hohl-arm-asm.pdf 

AWATI, R., 2022. What is interrupt in computing? Available from: https://www.techtarget.com/whatis/definition/interrupt 
