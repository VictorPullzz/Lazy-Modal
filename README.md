# Lazy-Modal
#### Simple and functional plugin for modals window!

## Advantages:
- Simple
- Adaptive
- Cross-browser
- Customize

# Settings:

- <b>position</b> ( position modal window ) <br>
  val: top, bottom, center, left, right | - px
 
- <b>content</b> ( the content that will be placed in the modal window ) <br>
  val: jQuery | - element $("..")

- <b>bcgcolor</b> ( background color ) <br>
  val: color | - #fff or rgba(0, 0, 0, 0.7)

- <b>positionclose</b> ( position element for closing modal window ) <br>
  val: outside or inside | string
  
- <b>closeoutside</b> ( when this parametr set true, then modal window close after click outside bacground ) <br>
  val: true or false | bool
  
- <b>effectshow</b> ( effect with which the modal window opens and closes ) <br>
   val: fade, top, bottom, left, right, zoom | string

- <b>type</b> ( type query ) <br>
   val: html or ajax | string
   
- <b>customclass</b> ( A custom class to be added to the structure ) <br>
   val: "" | string

- <b>basetpl</b> ( base template lazy-modal structure ) <br>
   val: '<div class="lazy-modal"><div class="lazy-modal-background"></div><div class="lazy-modal-scroll"><div class="lazy-modal-area-close"></div><div class="lazy-modal-container"></div></div></div>' | string

- <b>btnclosetml</b> ( base template close btn ) <br>
   val: '<button data-lazymodal-close class="lazy-modal-close">{..svg..]</button>' | string


# Events:
