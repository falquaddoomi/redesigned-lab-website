---
---

# Faisal's Terrible Website

Havoc reigns as the autobots roll out, crushing everything in their path.
A lone developer, armed with a Nokia brick, has holed himself up in a
crevice formed between two fallen buildings. He furiously T9's out the
first few bars of Vivaldi's "Spring" as a polyphonic ringtone.

Media!

![](https://www.youtube.com/watch?v=Ptk_1Dc2iPY)

{% include section.html %}

{%
  include section.html
  background="images/marigold_sultry.jpg"
  dark=true
  size=full
%}
## Component Tests

### Section

-- above component tests --

### Figure

{%
  include figure.html
  image="images/marigold_sultry.jpg"
  caption="The cat at its annual Christmas party, 1873"
  link="team"
  width="400px"
%}

### Button

{%
  include button.html
  type="github"
  link="some_github_handle"
  icon="fa-brands fa-github"
  text="Follow us on GitHub"
  tooltip="Follow us on GitHub for new releases"
  flip=true
  style="bare"
%}

### Citation

{%
  include citation.html
  lookup="doi:10.1371/journal.pgen.1007752"
  style="rich"
%}

### List

{%
  include list.html
  data="projects"
  component="card"
  filters="group: featured"
  style="rich"
%}

### Feature

{% capture cat_info %}
<p>Our cat is made up of people from all around the globe.</p>

<p>Cats have seven cervical vertebrae (as do most mammals); 13 thoracic vertebrae (humans have 12); seven lumbar vertebrae (humans have five); three sacral vertebrae (as do most mammals, but humans have five); and a variable number of caudal vertebrae in the tail (humans have only three to five vestigial caudal vertebrae, fused into an internal coccyx).  The extra lumbar and thoracic vertebrae account for the cat's spinal mobility and flexibility. Attached to the spine are 13 ribs, the shoulder, and the pelvis.  Unlike human arms, cat forelimbs are attached to the shoulder by free-floating clavicle bones which allow them to pass their body through any space into which they can fit their head.</p>
{% endcapture %}
{%
  include feature.html
  image="images/marigold_sweet.jpg"
  link="team"
  title="Meet our Cat"
  text=cat_info
  flip=true
%}

### Icon

{%
  include icon.html
  icon="fa-solid fa-heart"
%}

###  Card

{%
  include card.html
  image="images/marigold_cute.jpg"
  link="https://nasa.gov/"
  title="A Large Cat"
  subtitle="A cool cat"
  description="A cool cat"
  tooltip="A tip about a cool cat"
  tags="tag A, tag B, tag C"
  repo="greenelab/lab-website-template"
  style="small"
%}

### Portrait

{%
  include portrait.html
  lookup="jane-smith"
  style="small"
%}

### Post Excerpt

{%
  include post-excerpt.html
  lookup="2020-07-02-example-post-3"
%}

Attempt 2

{%
  include post-excerpt.html
  lookup="example-post-3"
%}

Attempt 3 (mine)

{%
  include post-excerpt.html
  lookup="my-test-post"
%}

Attempt 4 (mine, by title)

{%
  include post-excerpt.html
  lookup="a-cool-post"
%}

### Tags

{%
  include tags.html
  tags="ovarian cancer, dataset, gene expression"
  repo="your-lab/some-repo"
  link="blog"
%}

### Float

{% capture content %}
  Yowza, I've been hit!
{% endcapture %}

{%
  include float.html
  content=content
  flip=true
%}

### Grid

{% capture grid_content %}
  <p>Alpha</p>
  <p><b>Beta</b></p>
  <p><i>Gamma</i></p>
  <p><i><b>Epsilon</b></i></p>
{% endcapture %}

{%
  include grid.html
  content=grid_content
  style="square"
%}

### Cols

{% capture col1_text %}
  <p>Alpha</p>
  <p><b>Beta</b></p>
  <p><span style="color: red;">Delta</span></p>
{% endcapture %}

{% capture col2_text %}
  <p><i>Gamma</i></p>
  <p><i><b>Epsilon</b></i></p>
{% endcapture %}

{%
  include cols.html
  col1=col1_text
  col2=col2_text
%}

### Search

{% include search-box.html %}
{% include search-info.html %}

### Site Search

{% include site-search.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="tools"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
