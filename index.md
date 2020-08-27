<body>
    {% capture homeRow %}{% include homeRow.md %}{% endcapture %}
    {{ homeRow | markdownify }}
</body>

# Scotten Sound is currently down for maintenance.
Everything visible is for testing purposes **ONLY** nothing is permanent or finalized.

#### TODO
- [x] Figure out how to do inclusive markdown text (DONE)
- [ ] About Page
- [ ] Portfolio
- [ ] Education / Background

<body>
    {% capture homeRow %}{% include test.md %}{% endcapture %}
    {{ homeRow | markdownify }}
</body>

<footer class="site-footer">
    {% include footer.md %}
</footer>
