### Controller Prototyping and Iteration

One important part of my experience in the Digital Fabrication Lab was developing the spherical controller for *The Dream of Ball*. The controller was designed as a capsule-like object that could be opened and closed by twisting two halves together.

The first challenge came from the 3D printing process itself. Some areas required support structures, and the surfaces touching the supports became rough and uncomfortable to hold. In the initial version, the outer surface faced downward during printing, which caused visible marks and reduced the quality of the surface.

To improve this, I changed the orientation of the model and placed the supports inside the sphere instead. Although the inner surface became rougher, the outside became smoother and more pleasant to touch. This helped me understand how print orientation directly affects the tactile quality of a physical interface.

Another issue appeared in the locking mechanism. I originally used a threaded connection between the two halves. However, because the sphere was relatively small and the thread pitch was large, the assembled controller had several millimetres of play. The shell could move slightly during use, and there was a risk that wires inside the controller might become damaged or that the sphere could accidentally open.

Rather than redesigning the entire thread structure, I applied paper masking tape inside the shell to increase friction and reduce unwanted movement. This simple solution proved effective and showed me that not every problem requires a complex redesign.

The internal space of the controller also became an ongoing challenge. My first prototype had a diameter of 10 cm, but once the threaded structure was added, the usable internal space became too limited for the electronics. I then increased the diameter to 15 cm, but the Arduino boards, breadboards, batteries, solenoid, and wiring still could not fit comfortably inside.

Eventually, I produced a larger 20 cm version. Because of the limited build volume of the printer, each half had to be printed separately, which significantly increased the fabrication time. Although this process was sometimes frustrating, it taught me that physical prototyping often involves balancing ergonomics, internal components, fabrication constraints, and assembly requirements.

