## JavaScript Snippet Pack for Visual Studio

[![Build status](https://ci.appveyor.com/api/projects/status/qogg94i8nry0g0j7?svg=true)](https://ci.appveyor.com/project/madskristensen/javascriptsnippetpack)

Download this extension from the
[VS Gallery](https://visualstudiogallery.msdn.microsoft.com/423eb4a3-215f-4a8f-9287-1512618ffda3)
or get the
[nightly build](http://vsixgallery.com/extension/2a20580c-7be4-4440-bcd6-8dcf5aa2004e/).

-----------------------------------------

A snippet pack to make you more productive working with JavaScript.
Based on the [Atom snippets](https://atom.io/packages/javascript-snippets).


![Snippet manager](art/snippet-manager.png)

Here's the full list of all the snippets:

## Console

### [cd] console.dir

```javascript
console.dir(${1:obj});
```

### [ce] console.error

```javascript
console.error(${1:obj});
```

### [ci] console.info

```javascript
console.info(${1:obj});
```

### [cl] console.log

```javascript
console.log(${1:obj});
```

### [cw] console.warn

```javascript
console.warn(${1:obj});
```

### [de] debugger

```javascript
debugger;
```

## DOM

### [ae] addEventListener

```javascript
${1:document}.addEventListener('${2:event}', function(e) {
	${0:// body...}
});
```

### [ac] appendChild

```javascript
${1:document}.appendChild(${2:elem});
```

### [rc] removeChild

```javascript
${1:document}.removeChild(${2:elem});
```

### [cel] createElement

```javascript
${1:document}.createElement(${2:elem});
```

### [cdf] createDocumentFragment

```javascript
${1:document}.createDocumentFragment(${2:elem});
```

### [ca] classList.add

```javascript
${1:document}.classList.add('${2:class}');
```

### [ct] classList.toggle

```javascript
${1:document}.classList.toggle('${2:class}');
```

### [cr] classList.remove

```javascript
${1:document}.classList.remove('${2:class}');
```

### [gi] getElementById

```javascript
${1:document}.getElementById('${2:id}');
```

### [gc] getElementsByClassName

```javascript
${1:document}.getElementsByClassName('${2:class}');
```

### [gt] getElementsByTagName

```javascript
${1:document}.getElementsByTagName('${2:tag}');
```

### [ga] getAttribute

```javascript
${1:document}.getAttribute('${2:attr}');
```

### [sa] setAttribute

```javascript
${1:document}.setAttribute('${2:attr}', ${3:value});
```

### [ra] removeAttribute

```javascript
${1:document}.removeAttribute('${2:attr}');
```

### [ih] innerHTML

```javascript
${1:document}.innerHTML = '${2:elem}';
```

### [tc] textContent

```javascript
${1:document}.textContent = '${2:content}';
```

### [qs] querySelector

```javascript
${1:document}.querySelector('${2:selector}');
```

### [qsa] querySelectorAll

```javascript
${1:document}.querySelectorAll('${2:selector}');
```

## Loop

### [fe] forEach

```javascript
${1:myArray}.forEach(function(${2:elem}) {
	${0:// body...}
});
```

### [fi] for in

```javascript
for (${1:prop} in ${2:obj}) {
	if (${2:obj}.hasOwnProperty(${1:prop})) {
		${0:// body...}
	}
}
```

## Function

### [fn] function

```javascript
function ${1:methodName} (${2:arguments}) {
	${0:// body...}
}
```

### [afn] anonymous function

```javascript
function(${1:arguments}) {
	${0:// body...}
}
```

### [pr] prototype

```javascript
${1:ClassName}.prototype.${2:methodName} = function(${3:arguments}) {
	${0:// body...}
}
```

### [iife] immediately-invoked function expression

```javascript
(function(window, document, undefined) {
	${0:// body...}
})(window, document);
```

### [call] function call

```javascript
${1:methodName}.call(${2:context}, ${3:arguments})
```

### [apply] function apply

```javascript
${1:methodName}.apply(${2:context}, [${3:arguments}])
```

### [ofn] function as a property of an object

```javascript
${1:functionName}: function(${2:arguments}) {
	${3:// body...}
}
```

## JSON

### [jp] JSON.parse

```javascript
JSON.parse(${1:obj});
```

### [js] JSON.stringify

```javascript
JSON.stringify(${1:obj});
```

## Timer

### [si] setInterval

```javascript
setInterval(function() {
	${0:// body...}
}, ${1:delay});
```

### [st] setTimeout

```javascript
setTimeout(function() {
	${0:// body...}
}, ${1:delay});
```

## Misc

### [us] use strict

```javascript
'use strict';
```

### [al] alert

```javascript
alert('${1:msg}');
```

### [co] confirm

```javascript
confirm('${1:msg}');
```

### [pm] prompt

```javascript
prompt('${1:msg}');
```