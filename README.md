<h1 align="center">Reverse Shell Generator</h1>
<h2 align="center">Brendan Frisby</h2>

<h3 align="center">Original Author of HTML styled rev-shell-generators are tagged with credit below</h3> 

-------------------------------


#### My intentions are not to steal credit for anyones project. This is the BASE for my project that I will alter over time. Eventually it wont be recognizable, written in an entirely different language. It is my starting point and I plan to transition this HTML rev shell generator template to a more modern React, Next, Or Django app with some type of CMS/Backend to pull data from. I may even use Django, that way I can use Python sub proccesses to pull information directly from Msfvenom, making the application attentive to system to system differences. I'd just like to be clear the HTML template I am starting with is not mine. A good amount of the work has been abstracted away by the people listed at the bottom of this.

### Features

- Generate common listeners and reverse shells
- Save button to download Payloads from browser.
- Raw mode to cURL shells to your machine.
- Button to increment the listening port number by 1
- URI and Base64 encoding
- LocalStorage to persist your configuration
- Dark, Light and Meme Modes
- HoaxShell integration with custom listener (see link below for more information) | Credit: https://github.com/t3l3machus

### HoaxShell Listener Docs

[https://github.com/t3l3machus/hoaxshell/tree/main/revshells](https://github.com/t3l3machus/hoaxshell/tree/main/revshells)

### Screenshot

![image](https://user-images.githubusercontent.com/70012972/169376352-e6d6b90e-2e2e-46b0-b6f9-0e3f13713e39.png)

## Dev

It's recommended to use the netlify dev command if you're wanting to modify any of the server functions, such as for raw link support:

```
npx netlify dev
```

## Using Docker
Simply run the following commands within this repository to spin up the instance locally using a Docker container

```
docker build -t reverse_shell_generator .

docker run -d -p 80:80 reverse_shell_generator
```

Browse to http://localhost:80

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="http://ryanmontgomery.me"><br /><sub><b>Ryan Montgomery</b></sub></a><br /><a href="https://github.com/0dayCTF/reverse-shell-generator/pulls?q=is%3Apr+reviewed-by%3A0dayCTF" title="Reviewed Pull Requests">👀</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://briskets.io"><br /><sub><b>Chris Wild</b></sub></a><br /><a href="#projectManagement-briskets" title="Project Management">📆</a> <a href="#tool-briskets" title="Tools">🔧</a> <a href="#infra-briskets" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="#design-briskets" title="Design">🎨</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://papadope.net/"><br /><sub><b>Chris Papadopoulos</b></sub></a><br /><a href="#design-Papadope" title="Design">🎨</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.alanfoster.me/"><br /><sub><b>Alan Foster</b></sub></a><br /><a href="#infra-AlanFoster" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://muir.land"><br /><sub><b>AG</b></sub></a><br /><a href="#maintenance-MuirlandOracle" title="Maintenance">🚧</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/0x03f3"><br /><sub><b>Joseph Rose</b></sub></a><br /><a href="#ideas-0x03f3" title="Ideas, Planning, & Feedback">🤔</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/JabbaSec"><br /><sub><b>Jabba</b></sub></a><br /><a href="#data-JabbaSec" title="Data">🔣</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="http://www.jake-ruston.com"><br /><sub><b>Jake Ruston</b></sub></a><br /><a href="#data-Jake-Ruston" title="Data">🔣</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://h0j3n.github.io/"><br /><sub><b>Muhammad Ali</b></sub></a><br /><a href="#tool-H0j3n" title="Tools">🔧</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://sprucelab.site"><br /><sub><b>edrapac</b></sub></a><br /><a href="#tool-edrapac" title="Tools">🔧</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://epi052.gitlab.io/notes-to-self/"><br /><sub><b>epi</b></sub></a><br /><a href="#tool-epi052" title="Tools">🔧</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://skerritt.blog"><br /><sub><b>Brandon</b></sub></a><br /><a href="https://github.com/0dayCTF/reverse-shell-generator/commits?author=bee-san" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://robiot.github.io/"><br /><sub><b>Robiot</b></sub></a><br /><a href="#content-robiot" title="Content">🖋</a> <a href="#maintenance-robiot" title="Maintenance">🚧</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Hydragyrum"><br /><sub><b>Adam Bertrand</b></sub></a><br /><a href="#content-Hydragyrum" title="Content">🖋</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="http://rohitkumarankam.com"><br /><sub><b>Rohit Kumar Ankam</b></sub></a><br /><a href="#tool-rohitkumarankam" title="Tools">🔧</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/t3l3machus"><br /><sub><b>Panagiotis Chartas</b></sub></a><br /><a href="#infra-t3l3machus" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="#tool-t3l3machus" title="Tools">🔧</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

I want to thank this list of people as well. I've cloned this repo as a starting point to transition this to a react, next, or Django app instead. I want to sort of add it as a feature/widget to my portfolio/website. It's been a project I've been thinking about starting for awhile. I often use revshells.com and that is where this template came from. Open Source. 