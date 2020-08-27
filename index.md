<body>
    {% capture homeRow %}{% include homeRow.md %}{% endcapture %}
    {{ homeRow | markdownify }}
</body>

# Scotten Sound is currently down for maintenance.
Everything visible is for testing purposes **ONLY** nothing is permanent or finalized.

#### TODO
1. Figure out how to do inclusive markdown text (DONE)
2. About Page
3. Portfolio
4. Education / Background

<body>
    {% capture myInclude %}{% include test.md %}{% endcapture %}
    {{ myInclude | markdownify }}
</body>