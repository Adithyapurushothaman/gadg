gadg is a SPA (Single-page application) is a web app implementation that loads only a single web page and implements routing.
4 components are created using "ng g c comp_name" .
Inside the app.module.ts file we iported two packages HttpClientModule and RouterModule .
We added path inside the app.module.ts file by {path : 'Routerlinkname',component:componentname}.
inside the app.component.html we added a nav bar and added these router links by <a routerlink="Routerlinkname">.
