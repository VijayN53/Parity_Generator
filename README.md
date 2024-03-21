A Parity generator is a combinational logic circuit that generates a parity bit based on a set of data bits. Parity is a form of error-checking used in digital communication systems to 
detect errors in transmitted data.The basic idea behind parity is to add an extra bit to the data being transmitted such that the total number of bits set to 1 (or sometimes 0) is either odd or even, depending on the chosen parity scheme. This extra bit, called the parity bit, is used to check for errors during transmission.
There are two common types of parity: even parity and odd parity. In even parity, the parity bit is set to make the total number of bits set to 1 in the data, including the parity bit, even. 
In odd parity, the parity bit is set to make the total number of bits set to 1 in the data odd.

Here, I have written a verilog HDL module for parity generator and also obtained Block diagram , Circuit diagram and Test Bench WaveForm for the parity generator.
