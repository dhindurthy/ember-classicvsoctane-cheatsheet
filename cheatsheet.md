|   | Classic | Glimmer |
| --- | --- | --- |
| Lifecycle hooks | 13 | 2 lifecycle hooks <code>constructor willDestroy</code> <br/>Modifiers are the answer|
| Element or DOM based properties | 9 element/element customization properties/hooks | 3 properties: <code>isDestroying, isDestroyed, args </code> <br/> Modifiers, getters, tracked properties |
| Event handlers | 29 | Modifiers |
| Framework functions | 21 | None |
| Wrapper Element | Yes &quot;div&quot; usually <code>tagName, classNames, attributeBindings</code> | None |
| pass arbitrary HTML attributes directly to components <br/>Ex: <code>aria-labelledby</code> | adding a new argument to the component, and binding that argument to the attribute | Do it directly to component usage and add <code>...attributes</code> to wherever you want it in component.hbs <code><button ...attributes /button></code> |
| Arguments | As Component properties <code>this.filter('').then((results){})</code> | On the <code>args</code> property <code>this.args.filter('').then((results){}) </code>|
| Template-only components | No way without creating a class | Inbuilt feature like usual components and do without a Class |
| Stateless components | Yes | No |
| Initializing | <code>init(){}</code> | <code>constructor(){}</code> |
