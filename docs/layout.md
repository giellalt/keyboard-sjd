# Layout(s) for the Kildin Sami Keyboards

**Legend:**

| Mode                      | Standard | Dead   |
|---------------------------|----------|--------|
| Default                   | black    | green  |
| AltGr/Option              | red      | orange |
| Caps Lock (Mode Switch)   | blue     | pink   |
| Caps Lock + AltGr/Option: | purple   | green  |

# Кӣллт са̄мь кӣлл

![Кӣллт са̄мь кӣлл](./sjd_keyboards.svg)

<script>
    "use strict";

    var i, ii, nodes, node;

    nodes = document.querySelectorAll(".key-dead");
    for (i = 0, ii = nodes.length; i < ii; ++i) {
        nodes[i].addEventListener('click', function(e) {
            console.log(this);
        }, false);
    }
</script>

  
