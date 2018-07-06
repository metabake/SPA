
## Blog|Item example


```
   nbake -b
   cd blog
```

#### dat.yaml

dat.yaml has dual usage.

- One is static. Used to configure the pug page, and help with repeated fields. For example in SEO or to help when sharing item/content with a social network, for those that needed it.
- The other is dynamic:

```
   cd blog
   nbake -i .
```
That generates an items.json file that you can client side fetch, and bind dynamically.
