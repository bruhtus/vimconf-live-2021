## Vimconf Live 2021

This repo contains bruhtus' presentation and demo at vimconf live 2021. There are two ways you can see the presentation file:
- Use [sent by suckless.org](http://tools.suckless.org/sent/).
- Use the pdf version.

### Use sent by suckless.org

Here's the simplified step for those who want to use `sent` to display the slide:
- Download `sent` from suckless website.
- Extract the file.
- Change directory to the extracted directory or if you only extract the file you don't need to change directory.
- Compile `sent` by using `make` command.
- Check if it was working or not by using `./sent example`.
- If you decide you want to install `sent` on your system, you can use `sudo make install` command. And then display the presentation using `sent ~/path/to/presentation-file` command.
- If you just want to preview the presentation, you can use `./sent ~/path/to/presentation-file`.

### Side note

Please keep in mind that the demo was not supposed to be executable even tho the filetype is shell script. The filetype only for syntax highlighting and indentation, so it's not a real shell script. **Do not mindlessly make a script executable**.
