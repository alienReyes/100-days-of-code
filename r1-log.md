# #100DaysOfCode Log - Round 1 - [Rodrigo Reyes]

The log of my #100DaysOfCode challenge. Started on [January 1st, Wedensday, 2019].

## Log

### R1D1

Starting with my own blog, haven't decided if it should be Nuxt or Gridsome
I feel like Gridsome is a better option but Nuxt has the page transitions and localization options I need

### R1D2

- Seting up git bash on Hyper and VScode
  -updated Prettier settings and all that shit, that took days fucking VSCODE and windows

### R1D3

- Crisis averted, studied vue router learnt:

    1- You can guard routes with `beforeEnter` and `beforeLeave` 

    2- you can use webpack for lazyloading components
    ```
    const UserEdit= resolve=>{
    require.ensure(['./components/user/UserEdit.vue'],()=>{
        resolve(require('./components/user/UserEdit.vue'))
    },'user')
    ```
  ### R1D4

- VUEX not much to say

  ### R1D5
- more VUEX
this shit is incredible, remember use actions for asynch tasks and to pass arguments, arguments to this have to be objects, mutations are sync and some more like that

  
 
