### June 5th (1.5hr)
[NOTE: This was initally a Lapse timelapse but unfortunately Lapse did not work and all my footage got deleted]

- i have a clear goal in mind for this project: build a wireless split keyboard for under $50
- most wireless split keyboards online are more than $100
- i wanted something custom, yet budget
- im using xiao esp32c3 because it has an onboard battery charging circuit

- i started with the schematic:

<img width="527" height="638" alt="image" src="https://github.com/user-attachments/assets/bca812fc-f796-4b00-bce0-b2d563e852c8" />

- pretty standard other than the fact that there are two MCUs
- two MCUs? thats because im designing this PCB to be reversible

- then i went on to the PCB

<img width="793" height="518" alt="image" src="https://github.com/user-attachments/assets/c424a17f-db6c-4149-b419-3878021fabfc" />

- i realized that designing a reversible board would be tough
- i read some online forums and learned that there can be signal interference if two MCU footprints can be sandwiched
- ill have to figure that out tmrw
