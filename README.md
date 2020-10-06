# html-and-css-mini

Minimal setup to start hacking on a website using HTML & CSS.

```
git clone git@github.com:radekosmulski/website-mini.git
cd website-mini
npm install
# open index.html and styles.css in your favorite editor
npx live-server
```

If you make changes to either `index.html` or `styles.css` and save, the webpage should reload. You should be able to see the effects of changes that you've made in the browser without taking any additional actions.

## Exercises

There is also a way to use this repository to practice. I created exercises based on two fabulous resources: 

* [internetingishard](https://www.internetingishard.com/)
* [scrimba free css grid course](https://scrimba.com/learn/R8PTE)

My recommendation would be to go to the above, study the material and come here to do the exercises.

I list the exercises below. You can checkout the `starting` branch, see if you can implement the layout from the image and compare to the `done` branch. The starting branch will contain all the code you need to get started.

I work on these exercises [having the editor, image of what I am implementing and a browser window open on my screen](https://github.com/radekosmulski/html-and-css-mini/blob/images/images/me_doing_exercises.png?raw=true). By saving I can immediately see any changes that I have made. This is a really good environment for learning as it allows me to try out many things very quickly.

I also find having this [awesome flexbox cheatsheet](https://www.alsacreations.com/xmedia/guidelines/flexbox-cheatsheet.pdf) and this [wonderful grid cheatsheet](https://github.com/alsacreations/guidelines/blob/master/grid-cheatsheet.pdf) printed out on my desk very helpful.

### flexbox

| To implement  | starting branch | done branch | learning objective |
| ------------- | ------------- | ------------- | ------------- |
| <img src="https://github.com/radekosmulski/html-and-css-mini/blob/images/images/internetigishard_flexbox.png?raw=true" width="200" /> | https://github.com/radekosmulski/html-and-css-mini/tree/internetingishard_flexbox  | https://github.com/radekosmulski/html-and-css-mini/tree/internetingishard_flexbox_done | flexbox |
| <img src="https://github.com/radekosmulski/html-and-css-mini/blob/images/images/internetingishard_advanced_pos.png?raw=true" width="200" /> | https://github.com/radekosmulski/html-and-css-mini/tree/internetingishard_advanced_pos | https://github.com/radekosmulski/html-and-css-mini/tree/internetingishard_advanced_pos_done | advanced positioning |
| <img src="https://github.com/radekosmulski/html-and-css-mini/blob/images/images/internetingishard_menu.png?raw=true" width="200" /> | https://github.com/radekosmulski/html-and-css-mini/tree/internetingishard_menu | https://github.com/radekosmulski/html-and-css-mini/tree/internetingishard_menu_done | advanced positioning |
| <img src="https://github.com/radekosmulski/html-and-css-mini/blob/images/images/internetingishard_responsive_design.png?raw=true" width="200" /> | https://github.com/radekosmulski/html-and-css-mini/tree/internetingishard_responsive_design | https://github.com/radekosmulski/html-and-css-mini/tree/internetingishard_responsive_design_done | responsive design |

Now that you've exercised your flexbox skills, try [flexbox froggy](https://flexboxfroggy.com/)! It's a fun little browser game to help you practice what you've learned.

### grid

| To implement  | starting branch | done branch | learning objective |
| ------------- | ------------- | ------------- | ------------- |
| <img src="https://github.com/radekosmulski/html-and-css-mini/blob/images/images/scrimba_grid_3x2.png?raw=true" width="200" /> | [scrimba_grid_3x2](https://github.com/radekosmulski/html-and-css-mini/tree/scrimba_grid_3x2)  | [scrimba_grid_3x2_done](https://github.com/radekosmulski/html-and-css-mini/tree/scrimba_grid_3x2_done) | basic grid |
| <img src="https://github.com/radekosmulski/html-and-css-mini/blob/images/images/scrimba_grid_3x2_repeat_fr.png?raw=true" width="200" /> | [scrimba_grid_3x2](https://github.com/radekosmulski/html-and-css-mini/tree/scrimba_grid_3x2)  | [scrimba_grid_3x2_repeat_fr_done](https://github.com/radekosmulski/html-and-css-mini/tree/scrimba_grid_3x2_repeat_fr_done) | <ul><li>repeat(..., ...)</li><li>grid-template</li><li>fr /auto</li><ul> |
| <img src="https://github.com/radekosmulski/html-and-css-mini/blob/images/images/scrimba_grid_miniwebsite.png?raw=true" width="200" /> | [scrimba_grid_miniwebsite](https://github.com/radekosmulski/html-and-css-mini/tree/scrimba_grid_miniwebsite)  | [scrimba_grid_miniwebsite_done](https://github.com/radekosmulski/html-and-css-mini/tree/scrimba_grid_miniwebsite_done) | <ul><li>grid-column/row-start/end</li><li>gird-row/column</li><li>span, -1</li><ul> |
| <img src="https://github.com/radekosmulski/html-and-css-mini/blob/images/images/scrimba_grid_template_areas.png?raw=true" width="200" /> | [scrimba_grid_template_areas](https://github.com/radekosmulski/html-and-css-mini/tree/scrimba_grid_template_areas)  | [scrimba_grid_template_areas_done](https://github.com/radekosmulski/html-and-css-mini/tree/scrimba_grid_template_areas_done) | <ul><li>height: 100%</li><li>grid-template-areas</li><li>grid-area</li><ul> |
  
  ### Extras
  
  Branches demonstrating integrating other libraries with the basic setup available at `main`
  
| additional functionality  | branch name |
| ------------- | ------------- |
| <ul><li>jquery</li><li>google fonts</li></ul> | [extras_jquery_and_google_fonts](https://github.com/radekosmulski/html-and-css-mini/tree/extras_jquery_and_google_fonts) |
