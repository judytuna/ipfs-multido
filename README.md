# hyper-multido

Todo app with multiple "stages" of done-ness. I'm starting with video games.

View it live using the [Agregore browser](https://github.com/AgregoreWeb/agregore-browser) at: `hyper://0cff0e224c9f1a2def6f033d3e620c48c3db233171cf8eb6837cf26a7deb1e2d/`

<img width="518" alt="Screen Shot 2023-02-11 at 11 57 08 PM" src="https://user-images.githubusercontent.com/315395/218299625-1b38c633-a12e-431a-95ba-79601d46d07c.png">

### todo

 - [x] just to get started: very stupid todo list that is just a bunch of li elements in an unordered list (20 min)
 - [x] how to get html/js into a hyper or ipfs site (1 hr)
 - [x] plan out how to make the parts of the app (1 hr)
 - [x] name the app
 - [x] a list item can be in a different 'stage' (1 hr)
 - [ ] collapse list views into icons in one column
 - [ ] add "time added"
 - [x] save button (40 min)
 - [x] new game field
 - [ ] log every event to see a feed of changes
 - [ ] flip between list with indicator and multiple lists. vertical? horizontal like kanban board?
 - [ ] sorting a unified list (by date? by other things?)
 - [ ] tags on things? for example, "ongoing" (animal crossing) vs "progressing" (celeste). or "100%" vs "main objective completed"
 - [ ] popup should go away if you click outside it
 - [x] autosave per action (1 hr)
 - [x] add a legend so we know what the colors mean
 - [ ] edit a game's name
 - [ ] how does it look on android? (there is no iOS agregore)
 - [ ] fix colors and styling
 - [ ] pick a font
 - [ ] tutorialize!
 - [ ] general case - untie it from games?
 - [ ] other numbers of stages / arbitrary addition of stages?
 - [ ] delete a list item
 - [ ] pick bewteen color schemes, like "mario," "waluigi," and the default, "peach & rosalina" lol
 
 ### in my wildest dreams
 
 - [ ] follow friends' activity feeds
 - [ ] leave comments on friends' activity
 - [ ] review games i've played
 - [ ] track played time somehow (manually? input through steam api if there is one?)
 
 ### meta app ideas
 
 - list-maker: a GUI for setting up your own multido!
  - name of thing (books, video games, birds)
  - num stages
  - stage names
 
 ### out of scope
 
 - separating content and presentation. right now, data is kept as classes on list elements. lol 
 - an item can't be in more than one "stage" at a time. this is different from goodreads. maybe i can get around this by implementing tags, which are separate from stages.

