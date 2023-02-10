# uxgems
Patterns and algorithms for healthier user experiences

Pseudo and real code when possible. Quantify whenever possible (e.g. 3 beeps, not 2, not 4 and pref none).

Describe why and how an anti-pattern doesn't work.

Attention pollution. Design outside of the confines of the object - it exists in many contexts. e.g. airline app used both casually at home and urgently while in line.

- Notifiers
    - [Sounds](sounds.md)
    - typical frequencies and durations=
        - examples
        - algorithms
    - Haptic vibrations
        - typical frequencies and durations
        - examples
        - algorithms
    - Visual
        - use of red/yellow/green
        - cultural differences
    - Are there patterns to what makes something annoying across domains?

- General for now:        
    - Ambiguity when control has 2 states (which is on?)
    - moving a ui element as user trys to select
    - algorithms for pointer movement
    - palm cancellation
    - reflow around user obscuring the screen (like thumb over content)
    - snapping a dragged component to an alignment object (how does dragging a window to the side and having it snap there work?)

- Naming and language (maybe out of scope? maybe is it's own thing?)
    - other languages not only read right to left they process right to left e.g. the next arrow should point left, not right.
    - word research. Let's say I want to name my product or feature "cinq". How do people pronounce it? Is it a real word? Does it mean something in another language
    - slang and idiom checking for docs
    - Google's domain name finder is a useful tool for that context and gives lots of AI like insights.
    

- Urgency patterns

- Thresholds
    - simple smoothing algos such as kalman
    - dealing with absolute cutoffs (e.g. the slot is 100mm wide vs we only accept 100mm wide items)

- Chart of typical times and durations
    - Ex: startle and recover
    - Ex: how many questions in a row with "ok" as the answer everytime
    - holding dragged items over another item before it "opens". Like dragging files to a new folder - how long to wait on hover before expanding target? what constitutes intention?
    - how is hover intent determined? can you move mouse 1 pixel and the timer doesn't change?

- Time and dates
    - friendly times
    - intention to specifics, e.g. what does "set an alarm for 11" translate to?

- Large stuff:
    - UX flow for signup/login/forgot with business conditionals

- Breakdowns and analysis of good vs OK design. Maybe some bad design where it _should_ have been good but didn't work for reason X.

- Unpatent:
    - Area where users can document an idea so as to disclose and establish prior art


