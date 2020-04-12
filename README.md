Whether App Using Laravel & vue & tailwindCss

1. install a fresh laravel prolect:


composer create-project --prefer-dist laravel/laravel blog


Now 

2. install node js & Npm :

npm install 


Now initial tailwind css :


npm init -y


Now install tailwind css 


npm install tailwindcss

Now add all css files in the laravel project :

3. create a folder inside resource and create a file :
resource → css → main.css

@tailwind base;

@tailwind components;

@tailwind utilities;
4. Now add Laravel Mix files in the project :

Go to ,
webpack.mix.js  →

paste:

.postCss('resources/css/main.css', 'public/css', [
  require('tailwindcss'),
])


its include all component files input as output ,



5. Now initialize tailwind config file in the root directory :

create a file:

tailwind.config.js  , And paste:

// tailwind.config.js
module.exports = {
  theme: {},
  variants: {},
  plugins: [],
}

6. Now initialize BrowserSync in the project

go to the 

https://laravel.com/docs/7.x/mix#browsersync-reloading

add Browser syncronise files in the webpack.mix.js

.browserSync('vue-whether-app.test');


ekhane “vue-whether-app” holo amra jei app ta toiri krbo 

Now our project is ready for work



7. initialize our .editorcofig

Add :

[*.{js,vue,css}]
indent_size = 2


8. Now install All components of Vue :

composer require laravel/ui
php artisan ui vue


then :

npm install 
npm run watch




check its working:

<div id="app">
<example-component></example-component>
</div>



Change App name and location go to app.js

Vue.component('whether-app', require('./components/whetherApp.vue').default);



**********************First Day**********************************
