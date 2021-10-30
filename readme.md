These are the instructions for the [Game Dev Workshop](https://rubyconf.org/program/workshops#session-1190) at
RubyConf 2021. Here's a list of [all the workshops](https://rubyconf.org/program/workshops).

# Soup to Nuts: Build a Video Game Using Ruby!

Dreaming of building a video game was what got me into coding. If
you've ever had this childhood dream yourself, this workshop will help
that dream become a reality.

## Prerequisites

1. No programming experience is required for this workshop.

2. Create an account on [Itch.io](http://itch.io).

3. Download DragonRuby Game Toolkit. **This is commercial 2D game
engine and will be free to download from Oct 30, 2021 to
Nov 11, 2021: [follow this link to claim your free license](https://itch.io/s/58823/rubyconf-2021-kickoff)**.

4. Install a code editor. [Visual Studio Code](https://code.visualstudio.com/)
is beginner friendly.

## Getting Ready

1. After you have claimed your license to DragonRuby Game Toolkit,
   download the zip file.
2. Unzip the zip file.
3. Start DragonRuby (on Windows you'd double click `dragonruby.exe`,
   on Mac you'd double click `dragonruby`, on Linux you'd run
   `./dragonruby` from the Terminal).
4. You should see the following window pop up.
   <img width="1280" alt="start-screen" src="https://user-images.githubusercontent.com/517055/139538134-72b3efeb-76fc-4706-bab9-edd230aee375.png">
5. While DragonRuby is running, go to `./mygame/app/main.rb` in your code editor (the `mygame` directory is located within the unzipped contents).
6. The contents of the file should look something like this:
   ```ruby
   def tick args
     args.outputs.labels  << [640, 500, 'Hello World!', 5, 1]
     args.outputs.labels  << [640, 460, 'Go to docs/docs.html and read it!', 5, 1]
     args.outputs.labels  << [640, 420, 'Join the Discord! http://discord.dragonruby.org', 5, 1]
     args.outputs.sprites << [576, 280, 128, 101, 'dragonruby.png']
   end
   ```
7. Change the text `Hello World!` to `Hello RubyConf!` and save, you should see the game update to reflect the changes you've made. Here's what it should look like:

![update-code](https://user-images.githubusercontent.com/517055/139538537-403c8e15-2534-4be7-a709-dba9b16124d2.gif)
