##### yutms
###### (yet untitled task management system) v0.1.1
―

#### background

The biggest change in my workflow for a long time was when I've started using [Log](https://joshavanier.itch.io/log) late last year. From working without real focus and spending way too much passive time in front of the screen, I managed to change to a more focused and more efficient working time.

After a few months I've realized that Log is too strict for me. Focusing so much on the time part of logging required too much energy and focus.
I've designed a few other logging systems, but they had still too much friction (using and developing different tools, etc.).

yutms is a simple combined solution for a few problems I had: todo lists, notes, information gathering, logging.

It's my version of [lftm](https://github.com/CoralineAda/lftm).

![screenshot](https://github.com/kodedninja/yutms/blob/master/screenshot.png)

#### structure
```
journal/               the heart of the system. one directory for each month, one file for each week.
people/                notes for 1-on-1 meetings and friends
projects/              directory for every project that has unanswered questions (for group projects especially)
    meeting.txt           topics to discuss
	notes.txt             notes to remember

```
In the `journal` every day should be in its precise location. This results months with 5 weeks and weeks with less than 7 days.

#### usage
yutms is the middle layer of my daily task management (more detailed todos for micro, Google Calendar for the macro), so it doesn't contain time, space or detailed content.

Put into the __`Soon`__ list things that you'll do for sure (sooner or later).

The __`Maybe`__ list is for tasks that you may do, but you wouldn't be disappointed if they would get lost in the ocean of ideas.

__`Reminders`__ is for small things you want to remember (motivation, stuff you should not forget).

Try to work on tasks from the __`Soon`__. If you do something else, that's not a problem, but try to stick to these as much as you can. You can sort them by priority or in chronological order, but it's not obligatory.

Every time you finish a task from one of the lists pull it up to the current day. If you've completed something that's not on the list, just write it directly to the day. Note every task you completed.

I usually also tag my tasks with the name of the project they belong to. So the format of the task is `projectname: task`.

#### syncing
Right now I use Dropbox to sync it across devices, but this will change in the future. I also share it over Dat but only as a backup, yet.

#### changelog
##### 0.1.1
Directories in the `journal` have a new naming format: `i_name` (ex: `1_january`, `3_march`). This way they always stay sorted.
