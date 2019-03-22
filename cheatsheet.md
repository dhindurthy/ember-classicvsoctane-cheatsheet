|   | Classic | Glimmer |
| --- | --- | --- |
| Lifecycle hooks | 13 | 2 lifecycle hooksConstructorwillDestroyModifiers |
| Element or DOM based properties | **9**  element/element customization properties/hooks | 3 properties: isDestroying, isDestroyed,argsModifiers,_getters,_ tracked properties |
| Event handlers | 29 | Modifiers |
| Framework functions | 21 | none |
| Wrapper Element | Yes &quot;div&quot; usuallytagName, classNames, or attributeBindings | None |
| pass _arbitrary_ HTML attributes directly to componentsEx: aria-labelledby | adding a new argument to the component, and binding that argument to the attribute | Do it directly to component usage and add ...attributesto wherever you want it in component.hbs <button ...attributes /button> |
| Arguments | As Component properties this.filter(&#39;&#39;).then((results)=\&gt;{}) | On the args propertythis.args.filter(&#39;&#39;).then((results)=\&gt;{}) |
| Template-only components | No way without creating a class | Inbuilt feature like usual components and do without a Class |
| Stateless components | Yes | No |
| Initializing | Init(){} | Constructor(){} |
