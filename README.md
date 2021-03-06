# discourse-tag-sidebars

This theme component takes a topic and applies it as a sidebar for a tag's topic list. These sidebars are only visible when the browser is 767px or wider (most tablets and monitors). 

:eye: [Preview it on theme creator](https://theme-creator.discourse.org/theme/awesomerobot/discourse-tag-sidebars)


![34%20PM](https://meta-s3-cdn.freetls.fastly.net/optimized/3X/9/8/9884636155a0fce6394cecce7c8ae21ed5a1f687_2_1380x500.jpeg) 

 :thinking: https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682


## What can I do with this theme component? 

* Choose a topic and display its content as a sidebar for a tag. 

* Choose for the sidebars to appear on the left or the right of the topic list. 


## How do I configure it? 

Simply input the tag name and the id of the topic (e.g. [example.com/t/example-topic/](#)**57**)

![11%20PM](https://meta-s3-cdn.freetls.fastly.net/optimized/3X/7/7/77945845bf8057611e9b6badb26973efe1e18b83_2_1380x284.png) 

I recommend creating sidebar topics in their respective tags, closing the topic so there are no replies, and unlisting it (so it doesn't appear in the topic list). 

Note that you can not use a topic in a private category as a sidebar if you want it to be viewable outside of that category (you can, but users without access to that private topic will just see a blank sidebar!). 

## Custom CSS 

Each tag sidebar is wrapped with a class that contains the tag name, so for a tag named `test` that would be `.tag-sidebar-test`. You can use these classes to style the individual sidebars. 

The body tag on pages with sidebars also has a class added so you can use `body.custom-sidebar` to apply styles on all pages that have a sidebar. 

---

:heart: Special thanks to [@xrav3nz](https://github.com/xrav3nz) for laying the groundwork to make this component possible!
