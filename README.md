#[Vue](http:www.vuejs.org) Snippets for Sublime Text

---
###v

```
: {
}
```


###vue -  [Instance](http://vuejs.org/guide/instance.html)
```
var ${1:vm} = new Vue({
	
	${2:el: "${3:#demo}"}${4:}

})
```


###vued -  [Directive](http://vuejs.org/guide/custom-directive.html)
```
Vue.directive('${1:my-directive}', {
    
    bind: function () {
        ${2://content}
    },
    
    update: function (value) {
        ${3://content}
    },
    
    unbind: function () {
        ${4://content}
    }
})
```

###vuef - [Filter](http://vuejs.org/guide/custom-filter.html)
```
Vue.filter('${1:my-filter}', function (value) {

    ${2://content}
    
})
```

###vuec - [Single file component](http://vuejs.org/guide/application.html#Single_File_Components)
```
<template>
</template>

<script>
  export default {
  }
</script>

<style lang="css">
</style>
```

###vue-http - [Http request](https://github.com/vuejs/vue-resource/blob/master/docs/http.md)
*requires vue-resouce
```
this.\$http('${1:url}',${2:data}, {method:'${3:method}'}).then(res => {
   console.log(res); 
}, err => {
    console.log(err);
});
```

###vue-http-get - [Http get request] (https://github.com/vuejs/vue-resource/blob/master/docs/http.md)
*requires vue-resouce
```
this.\$http.get('${1:url}',${2:data}, ${3:options}).then(res => {
   console.log(res); 
}, err => {
    console.log(err);
});
```

###vue-http-post - [Http post request](https://github.com/vuejs/vue-resource/blob/master/docs/http.md)
*requires vue-resouce
```
this.\$http.post('${1:url}',${2:data}, ${3:options}).then(res => {
   console.log(res); 
}, err => {
    console.log(err);
});
```


#####Update - Just Remove and Install again.
