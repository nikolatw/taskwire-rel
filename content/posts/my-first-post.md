+++
title = "Taskwire is released."
date = "2022-07-31T19:20:16+02:00"
author = "Nikola"
showFullContent = true
readingTime = true
hideComments = true
+++

Version 1 (public beta) is now released.

Taskwire is an SSH client for the automation maintenance of routine tasks. As deploy or database migration. We invest very much in UX research. We are inspired to deliver the best experience and cover all modern developer's needs. Our target auditory is small startups and freelance developers where developers are doing server administration. The desktop application looks great. Taskwire is written using Flutter (Dart language) and uses Go to do secure SSH keys exchange.

Today we finished all v1 release tasks. Kanban boards with MVP labels now have all stickers in the "Done" column. It is a valuable achievement.

You can download [Taskwire for macOS](https://github.com/nikolatw/taskwire-rel/releases/download/v1/taskwire.zip) for free.

{{< image src="/00.png" alt="Hello Friend" position="center" style="border:#1b5ff3 10px solid;" >}}

Your data is secured by a passcode.

{{< image src="/0.png" alt="Hello Friend" position="center" style="border:#1b5ff3 10px solid;" >}}

You can have the main screen with dozens of tasks. (basically, the task is a few steps that usually form a bash script).

{{< image src="/1.png" alt="Hello Friend" position="center" style="border:#1b5ff3 10px solid;" >}}

You can add and edit tasks to achieve maximum productivity and automation.

{{< image src="/2.png" alt="Hello Friend" position="center" style="border:#1b5ff3 10px solid;" >}}

While working on this new task, you can test it against the target machine over SSH.

{{< image src="/3.png" alt="Hello Friend" position="center" style="border:#1b5ff3 10px solid;" >}}

You can see the output of commands.

{{< image src="/4.png" alt="Hello Friend" position="center" style="border:#1b5ff3 10px solid;" >}}

And for sure, you can run the task by clicking one button on the task card from the main screen :)

{{< image src="/5.png" alt="Hello Friend" position="center" style="border:#1b5ff3 10px solid;" >}}

You can have many-many machines to manage with Taskwire. We support mostly any ssh clinets, and most of OS. Linux (Ubuntu, Fedora... Alpine), MacOS, Android* and Windows.

{{< image src="/6.png" alt="Hello Friend" position="center" style="border:#1b5ff3 10px solid;" >}}

And security is made easy! You set the passphrase (passcode) once, and after that, Taskwire will create an RSA key for each connection. Securely put it in the authorized keys on your target machine. And that's it!

{{< image src="/6.5.png" alt="Hello Friend" position="center" style="border:#1b5ff3 10px solid;" >}}

You also can SSH into machine directly to perform one-time task.

{{< image src="/7.png" alt="Hello Friend" position="center" style="border:#1b5ff3 10px solid;" >}}

SSH terminal supports colors.

{{< image src="/8.png" alt="Hello Friend" position="center" style="border:#1b5ff3 10px solid;" >}}

Taskwire SSH client is interactive. You can use the VIM from shell mode.

{{< image src="/9.png" alt="Hello Friend" position="center" style="border:#1b5ff3 10px solid;" >}}