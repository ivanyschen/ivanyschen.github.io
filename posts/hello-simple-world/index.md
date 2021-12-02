<!--
.. title: Hello Simple World
.. slug: hello-simple-world
.. date: 2021-12-01 15:01:56 UTC-08:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
-->

Simple is complex.

<form method="POST" action="https://staticman-simple-is-complex.herokuapp.com/v3/entry/github/ivanyschen/ivanyschen.github.io/master/comments">
  <input name="options[redirect]" type="hidden" value="https://ivanyschen.github.io">
  <!-- e.g. "2016-01-02-this-is-a-post" -->
  <input name="options[slug]" type="hidden" value="{{ page.slug }}">
  <label><input name="fields[name]" type="text">Name</label>
  <label><input name="fields[email]" type="email">E-mail</label>
  <label><textarea name="fields[message]"></textarea>Message</label>
  
  <button type="submit">Go!</button>
</form>
