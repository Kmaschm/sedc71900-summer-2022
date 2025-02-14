# Daily Assignments / Notes

## Day 0 - July 12
  * Class intro
  * What is CS?
  * Why teach CS?
  * What has worked for you as a learner?
  * Difficulties in teaching and learning computer science?
  * Assignment:
    - Have a lesson plan available to share and discuss in class on Wednesday. If you have taught CS, use a CS lesson. If you have not had to create a lesson plan ever, spend time thinking about what a lesson plan would look like.


## Day 1 - July 13
  * Recap "What is CS?" discussion.
  * Lesson plan review ("talk shop", share protips/techniques)
  * Lesson plan writing

    ```
    Teams for Lesson Plan Work:
    1	Yeidy L	Alana R	Ashley U	Théa W	Vanessa Z
    2	Tanya W	Alise B	Christopher D	adam d
    3	Benjamin E	Patti E	William L	Kate M
    4	Saranii M	Greg S	Jerusha T	Maxwell Y
    5	Seth A	usman a	Joel B	Latoya B
    6	Aasine C	Dave C	Nicole C	Charles D
    7	Harrison F	stacy G	Taylor G	Ed H
    8	Shana Elizabeth H	Kiana H	Joshua H	Rachel K
    9	Erwin L	Amanda L	Jenna L	Sam L
    10	Christine M	Kirk M	Sarah M	Parmanand M
    11	David M	Jihae P	Mike P	Richard P
    12	Adam P	Michael R	Elizabeth R	Yanique S	Steve S
    13	Suzie S	Marisa S	Marieke T	Wayne T
    14	Alicia W	Jing X	Yenmin Y	Jessica N
    ```


## Day 2 - July 14
  * Pair programming
  * Collaborative lesson planning

#### Activity :: Pair Programming (be-the-student version)
  - Pair-program the given functions.
  - Coding car stuck? "Wave your team flag" by posting `:alert:` to main slack.
  - Use KtS liberally. If possible, note pedagogical aspects.
  - Function descriptions and sample output:

  `barGraphify(nums)` takes a list of non-negative integers and prints a horizontal bar for each index, commensurate with the value at said index. _Exempli gratia,_ ... 
  
  for x = {0,1,2,3}:
  ```
  barGraphify(x) -> 
  0:
  1: =
  2: ==
  3: ===
  ```

  and for x = {1,0,3,2}
  ```
  barGraphify(x) -> 
  0: =
  1:
  2: ===
  3: ==
  ```

  `vertBarGraphify(nums)` takes a list of non-negative integers and prints a set of vertical bars visualizing the magnitude of the value at each index. _Exempli gratia,_ ... 
  
  for x = {0,1,2,3}:
  ```
  vertBarGraphify(x) -> 
        *
      * *
    * * *
  0 1 2 3
  ```

  and for x = {1,0,3,2}:
  ```
  vertBarGraphify(x) ->

      *
      * *
  *   * *
  0 1 2 3

  ```

#### Assignment :: Collaborative Lesson Planning:
  - As a crew (same lesson plan teams as yesterday), create a lesson plan for a concept covered in the pre-work or the first programming course in this program (not data structures).
  - This should be a lesson plan for your appropriate grade level.
  - You need **not** create supplemental materials like sample code, assignments, etc.
  - Use whatever file format is most convenient for you
  - Name the file **`01_lesson`** (with appropriate file extension) and put it in your **`methods`** folder.
  - For reference, here are the topics
    * Recursion
    * Conditionals
    * Methods
    * Loops
    * Methods/Decomposition/Algorithms
    * Early java
    * Strings
    * Data types / variables


## Day 3 - July 15
  * lesson planning (cont.)
  * livecoding

#### ACTIVITY: Code annotation for livecoding

Annotate the provided code as a plan for live coding using the TEACHER PROMPTS below.

teams:
```
1	Joel B	Wayne T	usman a	Alicia W
2	Taylor G	Latoya B	Nicole C	Alise B
3	William L	Saranii M	Rachel K	stacy G
4	Kiana H	Théa W	Marieke T	David M
5	Jessica N	Jenna L	Maxwell Y	Greg S
6	Michael R	Jerusha T	Yenmin Y	Benjamin E
7	Sam L	Mike P	Amanda L	Elizabeth R
8	Parmanand M	Tanya W	Aasine C	Harrison F
9	Jihae P	Yeidy L	Seth A	Shana Elizabeth H
10	Ed H	Kirk M	Patti E	Alana R
11	Steve S	Christine M	adam d	Christopher D
12	Ashley U	Yanique S	Suzie S	Adam P	Erwin L
13	Joshua H	Richard P	Sarah M	Dave C
14	Kate M	Vanessa Z	Jing X	Marisa S
```

TEACHER PROMPTS:
-  `PROVIDE` :: code snippets or comments you definitely want to provide
-  `STUDENT-PROMPT` :: a specifically-worded question you want to ask, or a general solicitation for input, etc
-  `MUST-ANSWER-Q` :: a question that must be resolved, that a majority of your class must understand before moving on
-  `BIG-IDEA` :: an introduction of a new topic, a connection to prior lesson or discussion for application here in code, etc.
-  `BEEG-REVEAL` :: this is gonna blow yer minds...
-  `DELIBERATE-ERROR` :: specific code snippet or a general approach that is a bad fit for the situation, is flat-out wrong, or will lead to a compile- or run-time error, etc.
-  `FIRSTDRAFT` :: code that will work for now, but which you intend to replace later
-  `REVISION vX` :: better versions of firstdraft code...


CODE:
This method should search through `data` and return the index of the first time `value` appears in `data`. If `value` is not in `data` return -1.
  ```java
  public int linearSearch(int value, ArrayList<Integer> data) {

    int foundIndex = -1;

    for (int i=0; i < data.size(); i++) {

      int element = data.get(i);

      if (element == value) {
        foundIndex = i;
        break;
        }
      }
    return foundIndex;
  }
  ```


## Day 4 - July 18
  * livecode planning (cont.)
  * code tracing

#### Assignment :: Create a livecoding plan of your own by annotating code.
  1. Come up with TNPG.
  1. Select a language to write a livecoding plan for.
  1. Select a task to write a livecoding plan for (ideally, this would be a piece of code you have already available, it could even be sample code provided to you in the programming/data structures course)
  1. Create your livecoding plan. You can use any combination of the TEACHER PROMPTS from the previous activity and your own reminders/symbols/notation.
  1. DELIVERABLE: Submit your livecoding plan as **`methods/02_livecode_LANGUAGE`** with the appropriate file extension for your plan. If your group creates a plan that includes drawing markup, a pdf or image file is acceptable.

#### Activity :: Table trace

teams for TRACING
```
1	myearwood	cdesilva	hfung	qzou
2	ylevels	kmaschmeyer	dmoste	aufret
3	lboland	jpark	mshuman	erechtin
4	abraick	mrandazzo	rkaufman	jtheobald
5	beckley	kherr	aprado	twilliams
6	shenry	sgoldstein	gsciame	twardally
7	jlin	alee		ncojuangco
8	cmarra	kmartin	tgrant-knight	dciolino-volano
9	smuller	pmohanlall	ssabaugh	sadams
10	mpark	ehawkins	adriggers	uahmed
11	rparker	jhiggins	jbianchi	acassara
12	arobinson	elara	sseccafico	pelfers-wygand
13	ysears	jnovilloargudo	yyoung	smccoy
14	wtobias	wlamorie	jxue	
15	awade	slojacono	mthomas	
```

## Day 5 - July 19
  * code tracing (cont.)


## Day 6 - July 20
  * cs unplugged

---

## Portfolio assignment

   Students are to create two detailed lesson plans,
   outlines and supporting materials for computer science. The lesson plans and outlines should include a description of the intended student
   audience and a detailed explanation of how multiple pedagogical techniques can be used in delivering the lesson.

   Each lesson plan should demonstrate different pedogogical techniques, though there may be some overlap.

   For example, if the lesson includes subgoal labeling, the project should include the finished desired code along with the subgoal labels included within.

   The plans can be sequential, or entirely separate.
   The plans must also be aligned to the New York State Standards for Digital Fluency and Computer Science.
   The completed assignment should be such that the portfolio can be given to any computer science teacher and they could deliver the lessons as intended.

---
