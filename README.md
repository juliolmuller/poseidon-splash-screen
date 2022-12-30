<h1 align="center">
  :fountain_pen: Animated Splash Screen
</h1>

<p align="center">
  <a href="#trophy-lessons-learned">Lessons Learned</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-technologies--resources">Technologies</a>
</p>

<p align="center">
  <img src="https://img.shields.io/static/v1?labelColor=000000&color=2e576b&label=created%20at&message=december%202022" alt="Creation Date" />

  <img src="https://img.shields.io/github/last-commit/juliolmuller/poseidon-splash-screen?label=updated%20at&labelColor=000000&color=2e576b" alt="Update Date" />

  <img src="https://img.shields.io/github/v/tag/juliolmuller/poseidon-splash-screen?label=latest%20version&labelColor=000000&color=2e576b" alt="Latest Version" />

  <img src="https://img.shields.io/static/v1?labelColor=000000&color=2e576b&label=PRs&message=welcome" alt="Pull Requests Welcome" />

  <img src="https://img.shields.io/github/license/juliolmuller/poseidon-splash-screen?labelColor=000000&color=2e576b" alt="Project License" />
</p>

<p  align="center">
  <img src="https://user-images.githubusercontent.com/44725817/210031064-fa01c805-7dcc-43fa-9d95-0321879b2b6c.gif" alt="Poseidon Splash Screen" />
</p>

This project is a proof of conceipt to develop a splash screen for SPA's (single page applications) using inline SVG and CSS, with cool and performant animations to make the application loading fun and less painful 😜. 

> DISCLAIMER: The brand/logo "_Poseidon_" does not represent an existing product. It was developed for the purpose of this PoC alone.

[Check out the page running!](https://juliolmuller.github.io/poseidon-splash-screen)

## :trophy: Lessons Learned

- Creating `CSS @keyframes` to define custom and multiple animations to HTML elements;
- Selecting SVG pieces (`<path />` tag) and applying animations separately to each one;
- Using browser devtools to manipulate CSS properties and define animations states;
- CSS properties related to `animation` and `transform` to create performant transitions;
- CSS pseudo selector `:empty`, to transition the splash screen to the SPA when it has finished loading;

## :rocket: Technologies & Resources

- HTML
- SVG
- CSS

---

:star2: Feel free to submit pull requests to improve this project.
