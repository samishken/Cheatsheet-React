## Component Lifecycle

* Lifecycle methods are methods each component can have that allow us to hook into the views when specific conditions happen (i.e. when the component first renders or when the component gets updated with new data, etc).
    * eg. when user switch from youtube app to another app, the developer      should pause/stop youtube app. 
* Each component has several “lifecycle methods” that you can override to run code at particular times in the process. Methods prefixed with will are called right before something happens, and methods prefixed with did are called right after something happens.


* There are two types of component lifecycle methods:

* Mounting lifecycle methods. e.g. What happens when the component is created? Was an initial state set? Methods:

    - constructor()
    - componentWillMount()
    - render()
    - componentDidMount()
    - componentWillUnmount()

* Updating lifecycle methods. e.g. Has state changed? Methods:

    - componentWillReceiveProps()
    - shouldComponentUpdate()
    - componentWillUpdate()
    - render()
    - componentDidUpdate()