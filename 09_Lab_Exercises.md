## Digital Fabrication Lab

The Digital Fabrication Lab was the space I used most throughout the term. Although only a small part of the final *Dream of Ball* project depended on fabrication, spending time in the lab influenced many of my ideas and experiments.

This year our school introduced several new Bambu Lab H2D printers！！！ which was exciting because the older printers were becoming quite outdated. The older machines were slower and the print quality was often inconsistent. The new printers made the process much more reliable. However, there were only a few machines available, and because they were mainly intended for other users, there was often a long waiting time before I could use them.

<img width="1280" height="1707" alt="719b0999df65b1c3d3f125a263b8f2ef" src="https://github.com/user-attachments/assets/1973fc4b-deae-4e86-a219-4dd51f89c761" />

<br><br>

Besides my final project, I also used the lab for different experiments and side projects.

One experiment explored how rotational motion from a motor could be converted into linear movement. I designed and printed several mechanical parts to test this idea and better understand physical mechanisms.

<img width="810" height="1440" alt="b29e163be79dddbacbf531bfe96c288b" src="https://github.com/user-attachments/assets/8bc5f82a-d8ba-4cc8-8f50-abd2271905ca" />

<br><br>

Another project involved a wearable hand-tracking device. I designed and printed a structural shell that helped attach the sensing components to a glove and keep them securely positioned on the hand. The device used magnetic sensors placed at each finger joint, allowing the system to estimate the bending angle of the fingers and reconstruct the overall hand posture. The printed parts mainly served as a support structure rather than as sensing elements themselves.

<img width="1707" height="1280" alt="9409dbcdb3c092195883ae257514c440" src="https://github.com/user-attachments/assets/87b3cf25-3ad8-4ade-a2d3-c61eab8e72fd" />

<br><br>

These projects were not directly related to *The Dream of Ball*, but they allowed me to explore fabrication, mechanisms, and physical interaction beyond the final assignment.


## Controller Prototyping and Iteration

One important part of my experience in the Digital Fabrication Lab was developing the spherical controller for *The Dream of Ball*. The controller was designed as a capsule-like object that could be opened and closed by twisting two halves together.

The first challenge came from the 3D printing process itself. Some areas required support structures, and the surfaces touching the supports became rough and uncomfortable to hold. In the initial version, the outer surface faced downward during printing, which caused visible marks and reduced the quality of the surface.

To improve this, I changed the orientation of the model and placed the supports inside the sphere instead. Although the inner surface became rougher, the outside became smoother and more pleasant to touch. This helped me understand how print orientation directly affects the tactile quality of a physical interface.

<img width="3024" height="3517" alt="a9867097eb029aa36bc3a3d95fc6b81e" src="https://github.com/user-attachments/assets/a28c869b-ac35-40cd-b122-31dbb22652fa" />

<br><br>

Another issue appeared in the locking mechanism. I originally used a threaded connection between the two halves. However, because the sphere was relatively small and the thread pitch was large, the assembled controller had several millimetres of play. The shell could move slightly during use, and there was a risk that wires inside the controller might become damaged or that the sphere could accidentally open.

Rather than redesigning the entire thread structure, I applied paper masking tape inside the shell to increase friction and reduce unwanted movement. This simple solution proved effective and showed me that not every problem requires a complex redesign.

The internal space of the controller also became an ongoing challenge. My first prototype had a diameter of 10 cm, but once the threaded structure was added, the usable internal space became too limited for the electronics. I then increased the diameter to 15 cm, but the Arduino boards, breadboards, batteries, solenoid, and wiring still could not fit comfortably inside.

Eventually, I produced a larger 20 cm version. Because of the limited build volume of the printer, each half had to be printed separately, which significantly increased the fabrication time. Although this process was sometimes frustrating, it taught me that physical prototyping often involves balancing ergonomics, internal components, fabrication constraints, and assembly requirements.




