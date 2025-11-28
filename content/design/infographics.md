---
# An instance of the Blank widget with a Gallery page element.
# Documentation: https://wowchemy.com/docs/getting-started/page-builder/
widget: blank

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 60

title: 
subtitle: 

design:
  columns: '1'

---

<p style="text-align: center;">Available for commissions - contact me for details!</p>

<div style="text-align: center;">
  {{< gallery album="infographics" filter="limit:7" >}}
</div>

<div style="text-align: center; margin-top: 1rem;">
  <button id="show-all-btn">Show all</button>
</div>

<div id="full-gallery" style="display:none; text-align:center; margin-top:20px;">
  {{< gallery album="infographics" >}}
</div>

<script>
document.getElementById("show-all-btn").addEventListener("click", function() {
  const full = document.getElementById("full-gallery");
  if (full.style.display === "none") {
    full.style.display = "block";
    this.innerText = "Hide";
  } else {
    full.style.display = "none";
    this.innerText = "Show all";
  }
});
</script>