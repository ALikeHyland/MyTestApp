# Your mission, should you choose it, is the following...
You will need to convert the boring, html application (use link in file "Angular.Material Exercise.docx" in sharebase)
to look and feel like the sleek, sample Angular.Material application (use link in file "Angular.Material Exercise Final Look.docx" in sharebase).

To do this, you must:
1. Convert the entire application to use Angular.Material buttons
   * you can read more about material buttons here: https://material.angular.io/components/button/overview
2. Convert the html template on the app.component to leverage Angular.Material
   * app.component will need to use material side-navs (you can read more about this on https://material.angular.io/components/sidenav/overview)
   * app.component will need to use material toolbars (you can read more about this on https://material.angular.io/components/toolbar/overview)
3. Convert the html template on the comic-card.component to leverage Angular.Material
   * comic-card.component will need to use material cards (you can read more about this on https://material.angular.io/components/card/overview)
   * comic-card.component will need to use material radio buttons (you can read more about this on https://material.angular.io/components/radio/overview)
4. Add icons to the application
   * you can just leverage the <mat-icon> selector (see here: https://material.angular.io/components/icon/overview 
  [just use the example on the overview page as a reference, we wont be working with .svg])
5. Add badges to the application
   * use this link as a reference: https://material.angular.io/components/badge/overview
   * you'll notice that I've commented out the "likeBadge:string" property in comic-card.
  you'll want to uncomment this and set your like badge's "matBadge" equal to likeBadge (remember!: {{ }})
