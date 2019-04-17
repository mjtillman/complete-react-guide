# React

#### Boilerplate
    import React from 'react';
    import ReactDOM from 'react-dom';
    
    class MyComponent extends Component {
        render() {
            return (
            
            );
        }
    } 
--- 
#### Import/Export
    import '<file>';
    
    export default <name>;
---
#### createElement Method
The cumbersome way to render:

    return React.createElement('<element to render>', '<config>', <children>);
    
#### Functional Component
    import React from 'react';
    
    const MyComponent = () => {
        return (
            <p>Hello World!</p>
        );
    }
    
    export default person;