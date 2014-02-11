#[Vue](http:www.vuejs.org) Snippets for Sublime Text

---
###v

```
: {

}
```


###vue -  [Docs](http://vuejs.org/api/)
```
var ${1:vm} = new Vue({
	
	${2:el: "${3:#demo}"}${4:}

})
```


###vued -  [Docs](http://vuejs.org/guide/directives.html)
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

###vuef - [Docs](http://vuejs.org/guide/filters.html)
```
Vue.filter('${1:my-filter}', function (value) {

    ${2://content}
    
})
```


#####Update - Just Remove and Install again.
