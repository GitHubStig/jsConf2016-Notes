# <https://2016.jsconf.asia/>

# Nov 25 Friday
## Electron - A developer story (https://github.com/zcbenz)
### Cheng Zhao - Light table developer
#### https://www.youtube.com/watch?v=JDtc1xdZ-a0
![](https://pbs.twimg.com/media/C0AZ4V6UoAAwcj4.jpg:large)
- started out with Atom Shell for Github, soon to be called Electron
- talks about how to maintain and open source project like this on Github
- review PRs one by one, answer and close all issues, guide contributors thru code reviews..
- be strict about PR, code quality is most important, refactor code after merging
- "bootstrap" script
  - building environments, installing submodules
- development documentations

---
## Ghost in the machine (Kelsy digital Nomad)
### Kelsey Breseman
#### <https://www.youtube.com/watch?v=H52HezWtmm4>
![](https://pbs.twimg.com/media/CzRen8-UkAAY5x0.jpg:large)
- How to talk to hardware
- Javascript firmware in 30 minutes
- made Tessel (node API for physical world)
- book Node.js for Embedded Systems from O'Reilly
- <https://github.com/Frijol/Singapore_demos>
- <https://tessel.io/>

---
## DevTools of the future
### Kenneth from Microsoft (Program Manager)
#### <https://www.youtube.com/watch?v=KxRX_HRGRo4>
![](https://pbs.twimg.com/media/CzIluMYUUAAM9ri.jpg:large)
- "In a few years, users won't know they are using a browser"
- Full stack developer nirvana
- Browser <-> Debugger( VSCODE ) <-> Node
- Trying to move DevTool out from the browser
- Stream old hardware from the cloud to test and debug and run

---
## Bootstrap a live streaming React Web App
### Chengxi Li from Tencent
#### https://www.youtube.com/watch?v=RHq6bEgeZD4
![](https://pbs.twimg.com/media/C0GB329UkAAQC3a.jpg:large)
- Why Html5 over native
  - (I think opens links directly to 'other app' )
  - Promotion Activity
- Live streaming basics
- React
  - ???
  - alot in common - use Extend
  - mixing stuff - use HOC

---
## Maze of the rats
### Simon Swain <https://github.com/simonswain>
#### https://www.youtube.com/watch?v=-IvDnvtJ93s
![](https://pbs.twimg.com/media/CzhfVZYUcAAXql0.jpg:large)
- <https://ratsofthemaze.com/>
- teach the algorithm of how to code a random maze
- show us how to code a search algorithm (BFS, DFS)
- show us how to code the rats to chase the player

---
## Automate your life using JS
### Vito Chin
#### https://www.youtube.com/watch?v=HzjwmFv_MWk
![](https://pbs.twimg.com/media/C0G7HxsVIAAPj72.jpg:large)
- <https://www.npmjs.com/package/jodot>

---
## Running your JS app for years on a coin cell
### ARM Internet of Things - Jan Jongboom from ARM
#### <https://www.youtube.com/watch?v=3HLRwcVqgFE>
![](https://pbs.twimg.com/media/Cye7Tm5UoAAQ4pP.jpg:large)
- <http://www.noderockets.com/>
- [Jerryscript](http://jerryscript.net/)
- <https://github.com/armmbed/mbed-js-example>
- <http://mbed.com/js>

---
## Improve your workflow
### Khang Hoang from Vietnam
#### https://www.youtube.com/watch?v=-EdJzB0O23U
![](https://pbs.twimg.com/media/C0Af8gFUAAEy8Fu.jpg:large)
- develop stuff on React native for Australian company
- Vision - hijacks JSON request and allows local re-get with modification
  - <http://github.com/khanghoang/vision>

---
## The API in 2017
### Tyson Hackwood and Hemanth HM
#### <https://www.youtube.com/watch?v=bHaH1Trqa-4>
![](https://pbs.twimg.com/media/CyFo2LlUsAAvNLn.jpg:large)
- Tyson from Brantree/Paypal, Hemanth from Paypal
- serving ads via websocket which cannot be blocked by adblocker
  - XMPP

---
## Stack Overflow - High Perf Achitecture
### Marco Ceconi
![](https://pbs.twimg.com/media/CyF7-u0UAAAurca.jpg:large)
- Durability
- Utility
- Beauty
- 160 sites now (cooking, japanese, etc)
- when started - 140m page view per month
- now 1b-1.2b a month (not to date)
- monitor server using OpServer (open source)
- build->analyze->measure->repeat
- (bash node and js much) C# lover
- people->tools->code->repeat

--
## Bridging Connections
### Chee An
#### https://www.youtube.com/watch?v=V0dKzbhtHpQ
![](https://pbs.twimg.com/media/Cz2_1MnVIAEE8wm.jpg:large)
- Thank you.

---
## { Live : JS }
### Ruth John, Martin Schuhfuss, Matt McKegg
#### <https://www.youtube.com/watch?v=Ody93kpAjAY&list=PL37ZVnwpeshFn7VjMHjenn8niUTYNe8O7>
![](https://scontent-kul1-1.xx.fbcdn.net/v/t1.0-9/15135898_983771505060266_3489954584104811876_n.jpg?oh=e09f20ab9cea587de3174ea1d9a9fc7d&oe=58B227BD)
- <http://slides.com/martinschuhfuss/jsconfasia-2016#/>

---
# Nov 26 Saturday
## GPU.JS - GPU Accelerated JavaScript
### Fazli Sapuan & Eugene Cheah @PicoCreator
#### <https://www.youtube.com/watch?v=nUAZxpE9s9w>
![](https://pbs.twimg.com/media/Czr1wxIVQAAjAkQ.jpg:large)
- gpu.min.js
- nobody writes webgl programs
 - 2d : pixi.js
 - 3d: three.js
- compiling to GLSL
  - 62 chars become 42xx characters
- hardware has bugs, shrodinger branch, case in point, Intel HD 2000 on Mac and Chrome
```
function(x) {
  if( x > 2 ) {
    return x;
  } else {
    return x * 2;
  }
  return 42; // shrodinger's branch
}
```
- https://gpu.rocks

---
## Performance Profiing for V8
### Dr. Franziska HinkelMann, Google V8
#### <https://youtu.be/B9igDWV5ZUg>
![](https://pbs.twimg.com/media/Cy0Jz-MUUAA40uh.jpg:large)
- Profiling V8
  - JIT
  - Inline Caches (IC)
  - Optimizing compiler
  - Matching code
- JIT - generate machine code during runtime, not ahead of time (AOT)
- Optimizing compiler
  - basic compiler runs first and collects informations, "hot functions" are the compiled by optimizing compiler.
  - Optimizing Compiler + IC = Speed
- `-js-flags="--trace_ic ... > trace.txt`
- `node --trace_opt -trace-depot load-opt.js`
- Be careful with optimizing
  - don't "optimize" unless you must
  - Measure first
  - Be careful with optimizing
    - V8 Internals change
    - Different in other engines
- `-chrome --js-flags="--trace-opt"`
- IC Explorer `v8/tools/ic-explorer.html`

---
## From Zero to Binary Search Tree
### James Kyle from Facebook
#### https://www.youtube.com/watch?v=bM5Wfmh9i5k
![](https://pbs.twimg.com/media/Cz3GJDLUsAEX420.jpg:large)
- Yarn
- FlowType
- Lerna
- <http://git.io/data-structures>

---
## Applying the magic of Neural Networks
### Lian Li @CHIMNEY42 - Datenfreunde
#### <https://www.youtube.com/watch?v=rZ_8xTX1LU4>
![](https://pbs.twimg.com/media/Czch8mwUUAA1_Er.jpg:large)
- Machine learning with Node.js
- Conclusion
  - work incrementally
  - think about the problem, not the solution
    - the machine will come up with the solution
  - try out different configuration parameters
  - It's all about the data

---
## NeuroJS: Capturing And Visualizing Brainwaves With Angular 2
### Alex Castillo <https://github.com/alexcastillo> from NetFlix
#### <https://www.youtube.com/watch?v=S7M2Dj-_fwU>
![](https://pbs.twimg.com/media/CyQUbDHVEAE3a8A.jpg:large)
- node gets data from hardware, web using websocket and connect and grabs data then visualize with charts.js and three.js all using Angular 2

---
## Wombat Driven Understanding (NPM spelled upside-down WDU)
### Raquel Veléz - works at caltech, mit and npm
#### <https://youtu.be/7MbXsRS-ZLg>
![](https://pbs.twimg.com/media/CzSWfwmUoAEjpX7.jpg:large)
- (npm is stronk!)
- slides [here](https://speakerdeck.com/rockbot/wombat-driven-understanding-an-interactive-guide-to-using-npm)

---
## Bundling With H2 Server Push
### Sebastian Deckers
#### <https://youtu.be/BPcjN_1qsdA>
![](https://pbs.twimg.com/media/Cyq0UtGUUAAmcB3.jpg:large)
- bundling at the protocol layer
- cache digest, sent from browser to tell sever what not to send
  - save bandwidth
- https://www.npmjs.com/package/unbundle
  - emoji encoded hash

---
## JS in the Enterprise
### Ashwin Vombatkere
#### https://www.youtube.com/watch?v=loh8MarYBfw
![](https://pbs.twimg.com/media/Cz77mxdVEAAoffC.jpg:large)
- unit test your non-functional business logics
- JS Churn causes alot of rewrite

---
## Hired - The Job Search and Opportunities in Tech
### Steven Gong from Hired
#### <https://youtu.be/b4y9-JZkgKI>
![](https://pbs.twimg.com/media/CyKzgZuUoAEOCBr.jpg:large)

---
## Node.js version
### Myles Borins from IBM
#### <https://youtu.be/3gkm7oafWxs>
![](https://pbs.twimg.com/media/CzsriuKUAAAE8mb.jpg:large)
- Smoke testing saves the day before release hits user land

---
## Coding Chat Bot
### Kahwee Teng (singaporean working in SF)
#### https://www.youtube.com/watch?v=c_hmwFwvO0U
![](https://pbs.twimg.com/media/Cz735TwUsAA_r1W.jpg)
- <https://speakerdeck.com/kahwee/coding-chatbots-in-node-dot-js>
- chat bot is another way to get to your users
- use <https://requestb.in>
- using localtunnel and nodemon
  - <https://localtunnel.github.io/www>
- how to resolve an intent, the intention of the user
  - regex is nice but not so straightforward
  - using simple NLP tools
    - nlp_compromise
    - <https://github.com/nlp-compromise/nlp_compromise>
    - require('gemoji') to parse invalid chars like apple
    - for natural date time parsing use 'chrono-node' package
- we build SG, exmple of structured chatbot
- structured services
  - Octane AI
  - api.ai
  - ..
- machine learning and NLP services
  - ..
- <https://github.com/kahwee/ranka>

---
## Exploring Future Node
### Yosuke Furukawa working at Recruit Technologies
#### <https://youtu.be/m1LxOLAFHSo>
![](https://pbs.twimg.com/media/Czxa4kCUoAA8Y9R.jpg:large)
- <https://speakerdeck.com/yosuke_furukawa/exploring-future-node>
- organizer/leader node festival (japan)
- creator of <http://hexi.pics>
- node v10 will have import from modules
  - maybe using `.mjs` file extension

---
## Evolution Of The Web
### Dr. Alexander Gouaillard
![](https://pbs.twimg.com/media/CyLdko4UcAAE764.jpg:large)
- Web is NOT Internet
  - internet is the plumbing, with a bunch of protocols (HTTP. email, dns, ip, tcp/ip)
  - web is about content (HTML mainly)
- Who made the internet and the web
  - internet: US goverment and the internet protocol
  - web: tim berners-lee and HTTP/HTMl
- Apple, Microsoft, Google and Mozila says they know what people want
  - but they are always arguing with each other. -- Dr Alex.
  - if you disagree, step up, we as developers should know best


Links
===
- <https://www.facebook.com/pg/JSConfAsia/photos/?tab=album&album_id=986230888147661>

