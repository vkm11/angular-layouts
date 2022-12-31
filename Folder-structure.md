# Demo
## Folder Structure
1) ng g c layouts/default
1.1) ng g m layouts/default/

2) ng g c layouts/fullwidth
2.1) ng g m layouts/fullwidth/
 
3) ng g c modules/home
4) ng g c modules/login
5) ng g c modules/posts

6) ng g m shared  // create module
6.1) ng g c shared/components/sidebar
6.2) ng g c shared/components/header
6.3) ng g c shared/components/footer
 
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.2.5.

C:\Users\vijay>cd desktop

C:\Users\vijay\Desktop>cd demo-example

C:\Users\vijay\Desktop\demo-example>cd demo

C:\Users\vijay\Desktop\demo-example\demo>ng g c layouts/default
CREATE src/app/layouts/default/default.component.html (22 bytes)
CREATE src/app/layouts/default/default.component.spec.ts (606 bytes)
CREATE src/app/layouts/default/default.component.ts (279 bytes)
CREATE src/app/layouts/default/default.component.css (0 bytes)
UPDATE src/app/app.module.ts (493 bytes)

C:\Users\vijay\Desktop\demo-example\demo>ng g c layouts/fullwidth
CREATE src/app/layouts/fullwidth/fullwidth.component.html (24 bytes)
CREATE src/app/layouts/fullwidth/fullwidth.component.spec.ts (620 bytes)
CREATE src/app/layouts/fullwidth/fullwidth.component.ts (287 bytes)
CREATE src/app/layouts/fullwidth/fullwidth.component.css (0 bytes)
UPDATE src/app/app.module.ts (595 bytes)

C:\Users\vijay\Desktop\demo-example\demo>ng g m layouts/fullwidth/
CREATE src/app/layouts/fullwidth/fullwidth.module.ts (195 bytes)

C:\Users\vijay\Desktop\demo-example\demo>ng g m layouts/default/
CREATE src/app/layouts/default/default.module.ts (193 bytes)

C:\Users\vijay\Desktop\demo-example\demo>ng g c modules/home
CREATE src/app/modules/home/home.component.html (19 bytes)
CREATE src/app/modules/home/home.component.spec.ts (585 bytes)
CREATE src/app/modules/home/home.component.ts (267 bytes)
CREATE src/app/modules/home/home.component.css (0 bytes)
UPDATE src/app/app.module.ts (677 bytes)

C:\Users\vijay\Desktop\demo-example\demo>ng g c modules/login
CREATE src/app/modules/login/login.component.html (20 bytes)
CREATE src/app/modules/login/login.component.spec.ts (592 bytes)
CREATE src/app/modules/login/login.component.ts (271 bytes)
CREATE src/app/modules/login/login.component.css (0 bytes)
UPDATE src/app/app.module.ts (763 bytes)

C:\Users\vijay\Desktop\demo-example\demo>ng g c modules/posts
CREATE src/app/modules/posts/posts.component.html (20 bytes)
CREATE src/app/modules/posts/posts.component.spec.ts (592 bytes)
CREATE src/app/modules/posts/posts.component.ts (271 bytes)
CREATE src/app/modules/posts/posts.component.css (0 bytes)
UPDATE src/app/app.module.ts (849 bytes)

C:\Users\vijay\Desktop\demo-example\demo>ng g m shared
CREATE src/app/shared/shared.module.ts (192 bytes)

C:\Users\vijay\Desktop\demo-example\demo>ng g c shared/components/footer
CREATE src/app/shared/components/footer/footer.component.html (21 bytes)
CREATE src/app/shared/components/footer/footer.component.spec.ts (599 bytes)
CREATE src/app/shared/components/footer/footer.component.ts (275 bytes)
CREATE src/app/shared/components/footer/footer.component.css (0 bytes)
UPDATE src/app/shared/shared.module.ts (287 bytes)

C:\Users\vijay\Desktop\demo-example\demo>ng g c shared/components/header
CREATE src/app/shared/components/header/header.component.html (21 bytes)
CREATE src/app/shared/components/header/header.component.spec.ts (599 bytes)
CREATE src/app/shared/components/header/header.component.ts (275 bytes)
CREATE src/app/shared/components/header/header.component.css (0 bytes)
UPDATE src/app/shared/shared.module.ts (380 bytes)

C:\Users\vijay\Desktop\demo-example\demo>ng g c shared/components/sidebar
CREATE src/app/shared/components/sidebar/sidebar.component.html (22 bytes)
CREATE src/app/shared/components/sidebar/sidebar.component.spec.ts (606 bytes)
CREATE src/app/shared/components/sidebar/sidebar.component.ts (279 bytes)
CREATE src/app/shared/components/sidebar/sidebar.component.css (0 bytes)
UPDATE src/app/shared/shared.module.ts (477 bytes)
