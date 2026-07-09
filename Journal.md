SESSION 1

So I found out about the program barely a few days ago and decided to make one. I didn't read the entire guide, so I started the CAD before going through it in order. I'm now finished with the CAD and schematic. Took about 2 hours. I might add an engraving to the Front left side of the case.

The schematic is going to be easy, I have it in my mind, just need to sketch it out. 




<img width="928" height="688" alt="Screenshot 2026-07-02 183326" src="https://github.com/user-attachments/assets/a89df7a4-59a1-4160-9d53-a9cc6c26626f" />


UPDATE TO SESSION 1

I switched a 3x3 matrix instead of a 4x4, which made more sense, and I also embossed my middle to the front.




<img width="906" height="631" alt="Screenshot 2026-07-02 191723" src="https://github.com/user-attachments/assets/0b950e5c-ce36-40c5-a33a-86888a6dbe2d" />



SESSION 2 (30-min)

schematic done!

I had to sacrifice the backlit adjustment with the code feature; it will be stuck to the highest setting. I might be able to change it with some resistors, but it won't change with code  

<img width="1273" height="608" alt="image" src="https://github.com/user-attachments/assets/c8647e7b-1ee7-4ba5-be33-e3b33e0aadde" />



SESSION 3 

Today I finished implementing the main challenge that makes the alarm clock unique. Instead of simply pressing a button to turn the alarm off, the firmware now generates a random sequence using all 9 switches arranged in the 3×3 matrix. Every time the alarm is triggered, the order is different, making each attempt unpredictable.
The sequence is displayed on the TFT screen, allowing the user a brief moment to memorise it before attempting to recreate it using the physical switches. The program continuously scans the switch matrix, compares each input against the expected switch in the sequence, and keeps track of the user's progress. Correct inputs advance to the next step, while a single incorrect switch immediately resets the challenge back to the beginning, forcing the user to start the sequence again.
Alongside the challenge logic, I integrated the buzzer so it continues sounding until the entire sequence has been completed successfully. The display also provides real-time



<img width="1025" height="753" alt="image" src="https://github.com/user-attachments/assets/e5a6d486-ae4f-4451-82fe-0560a0799d6e" />

