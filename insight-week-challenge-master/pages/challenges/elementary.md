---
layout: page
title: Elementary
permalink: /challenges/elementary
hide: true
---

#### The following list of elements contains a secret message:

Mercury,
Lead,
Thulium,
Polonium,
Polonium,
Actinium,
Americium,
Bismuth,
Tantalum,
Iridium,
Mercury,
Osmium,
Thulium,
Americium,
Lead,
Tantalum,
Lutetium,
Hafnium,
Polonium

---

<div class="wrap-collapsible">
    <input id="collapsible" class="toggle" type="checkbox">
    <label for="collapsible" class="lbl-toggle">Hint</label>
    <div class="collapsible-content">
        <div class="content-inner">
            <p>
                Every one of these elements maps to a character somehow...
            </p>
            <p>
                This <a href="https://pubchem.ncbi.nlm.nih.gov/periodic-table/">link</a> will probably be very helpful.
            </p>
        </div>
    </div>
</div>

---

<form>
    <label for="answer">Answer:</label><br>
    <input type="text" id="submission" name="submission"><br><br>
    <input type="submit" value="Submit" onclick="javascript:checkAnswer('elementary', document.getElementById('submission').value)">
</form>