# Project Proposal for iOS PT3 Build Sprint

1. Fork and Clone this repository
2. Fill out the information below
3. Tag your TL and Instructor on your Pull Request

## Requirements

1. Do you want to work Solo or on a Team: `<solo>`
2. [App Idea](https://github.com/LambdaSchool/iOS-Build-Week-1): `<Medication Tracker>`
3. App Description (3-5 sentences):
Track your medications and supplements with ease!  This app will help you remember to take your medications and supplements on time.
4. Target Audience: Anyone who has trouble remembering to take their medication.  Mostly elderly people.

## Brainstorming

Add photos, notes, and sketches from your brain storming session. 

1. Brainstorming (Photo / Sketch) (I will add this sketch tomorrow before class)
    1. 15 min: Mind Map 
    2. 15 min: Organize ideas
    3. 10 min: Sketch mock ups 
2. If you have tons of ideas, set a timer again and keep going.
3. Don't filter yourself in the brainstorming phase, you want to capture everything and anything

## Project Plan
1. List out your tasks
2. Organize your tasks by priority
    1. Add subtasks
    2. Be specific. Every goal should be concrete, otherwise it's not actionable. 
    3. Break down large tasks into smaller tasks that you can "cross off".
3. You won't be able to do everything, focus on ~3 features / 3-5 screens that you can finish
4. Re-evaluate your progress each day and plan what you'll work on the next day
    
    BASIC PLAN:
    1. Set up basic VC and files in Main Storyboard
        a. Initial VC
        b. Instruction VC
        c. View Med Table VC
        d. Add/Edit Med VC
    3. Configure Initial VC & Instruction VC
        a. Create buttons and configure respective segues in Initial VC
        b. Write instructions in Instruction VC
    4. Configure Med Table VC
        a. Create & configure Model and Model Controller(s)
        b. Create and Configure Cell Class
        c. Create buttons and connect Add/Edit Med VC
    5. Configure  Add/Edit Med VC
        a. Create and connect buttons and labels
        b. Configure persistence
        c. Configure timers and alerts for each medication
        STRETCH GOALS:
    6. Configure Calendar/Next Med List
        a. Have Initial VC show Day/Time/Medication/Dosage of next med
        b. Add Calendar (table?) VC to main storyboard and create class
        c. Show upcoming medication in chronological order (allow user to pick list or calendar view?)
        d. Update persistence and properties to include whether or not the user took meds on time or at all.
        e. Have historical med reminders show as red if not taken or green if taken (optional)
    7. Configure Print VC
        a. Add Print VC and related button+segue in Initial VC and create PrintVC class
        b. Add and connect buttons to print in either simplified or detailed (historical) views
        c. Configure simplified and historical view functionality
        

