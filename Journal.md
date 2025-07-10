## 6 July 2025 – 3 Hours
After weeks of dreaming, tonight I finally began working on my own keyboard one that would scream speed and personality. I wanted something more than just function; I wanted emotion. I call it the Mercboard, inspired by the Mercedes-AMG Petronas Formula 1 team. The idea is to blend clean circuitry with motorsport chaos  a PCB that not only works flawlessly but also looks like it's ready to hit the track. I started the layout on paper, roughly planning a 65-key matrix and listing the components I’d need. The ATmega32U4 was a no-brainer for its USB HID capability. With chai in one hand and a pencil in the other, I sketched the beginnings of what might become my fastest creation yet. The session lasted a little over three hours, and by the end, the name Mercboard had officially entered my notebook and my heart.


![image](https://github.com/user-attachments/assets/02c38862-8c2d-4f8c-9ee3-c617454d4246)





## 7 July 2025 – 4 hours
I sat down today with full focus to begin designing the schematic, and this time I was in flow. Using Eagle, I built out a 5x14 key matrix, carefully positioning every switch symbol like setting up components on a race car. The ATmega32U4 took the spotlight, and I began wiring it to each row and column with attention to current paths and layout clarity. Added decoupling capacitors, pull-down resistors, a USB mini connector, and a reset switch. For diode selection, I stuck to 1N4148s—reliable and easily sourced. The logic came together slowly but cleanly over nearly five hours. Cross-referencing every wire, I started imagining how the PCB would look. There was this quiet excitement, as if every net connected brought the board closer to life. When I finally hit "save," it felt like the electrical soul of the Mercboard was finally assembled and humming quietly on-screen.

![image](https://github.com/user-attachments/assets/3d76cd87-9b9d-41a6-8a18-bf0635fbbbea)


![image](https://github.com/user-attachments/assets/b9d045c3-650e-4d81-a0f9-0b65215b01ac)



## 8 July 2025 – 4-5 hours
Today was all about PCB art and trace routing. I imported the schematic and began laying out the board—every key switch placed with care like tires on a grid. But the real challenge was fitting in the image of the Mercedes-AMG F1 car into the silkscreen. I converted it into a usable vector format and brought it into the board editor, layer by layer. It wasn't just drag and drop—I had to shape traces, shift diodes, and reroute paths so they would dance around the car’s body without ruining the electrical performance. The car looks like it's racing across the key switches now. Routing the matrix in such a way that it didn't destroy the artwork took close to seven hours. I didn’t even realise when night turned into early morning. The board is starting to feel like more than a PCB—it is becoming a tribute to both design and discipline.

![image](https://github.com/user-attachments/assets/a8320661-8a33-492c-9f13-49e95a67cb1e)



![image](https://github.com/user-attachments/assets/8a2df745-b192-4a9b-8668-67cba5381522)



![image](https://github.com/user-attachments/assets/e9016803-fa1c-4f57-bd41-600840db1859)



![image](https://github.com/user-attachments/assets/e7e6c09f-3534-4eae-ad3d-b00219311c6a)


![image](https://github.com/user-attachments/assets/0fd322a0-f4ed-4fd2-9d81-70273c81552f)


## 09 July 2025 – 5 Hours
I wrapped up the final PCB design today after intense review. First, I ran the Design Rule Check and Electrical Rule Check—both came back with minor, non-critical issues, mostly silkscreen overlaps, which I cleaned up manually. Then I fine-tuned the F1 car’s placement to ensure no pads or vias were getting covered. Cross-verified switch footprints with datasheets, and aligned the USB port precisely using the mechanical layer references. The artwork was carefully shifted to avoid silkscreen errors. I also labeled every component and test point, thinking ahead for easy debugging. Every trace felt like a careful brush stroke on a canvas now. After another five hours of pure concentration, I zoomed out and took a look at the final board. It looked fast. It looked loud. It looked like Mercboard. A PCB not just meant to function, but to express something. Next step—prepare it for the world.

![Screenshot 2025-07-10 154817](https://github.com/user-attachments/assets/59573921-76e1-4d02-9ff2-668ed962d26b)

![Screenshot 2025-07-10 154753](https://github.com/user-attachments/assets/4b17208c-b055-4042-a68b-878d810f5db9)



![Screenshot 2025-07-10 150627](https://github.com/user-attachments/assets/6df6fda6-f0a6-4050-a780-800f777a94e1)



![image](https://github.com/user-attachments/assets/89f2f481-e315-4479-9225-882a1558e646)



![image](https://github.com/user-attachments/assets/9e5ca16e-2b61-4055-90ff-c752b4aec129)


