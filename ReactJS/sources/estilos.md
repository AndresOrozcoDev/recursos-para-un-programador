// Estilos en linea
import React from 'react';

const Component = () => {
  
  const h1Styles = { color: 'blue', fontSize: 32px, textAlign: 'center'}
  return (
    <h1 style={h1Styles}>
        Hola Mundo!
     </h1>
  )
};

export default Component;

// Estilos de hoja externa
import React from 'react';
import './styles.css';

const Component = () => {
  
  return (
    <h1 className="h1Styles">
        Hola Mundo!
     </h1>
  )
};

export default Component;

// Styled-components
import React from 'react';
import styled from 'styled-components';

const Button = styled.button'
  background-color: blue;
  color: white;
  padding: 5px 15px;
'

const Component = () => {
  
  return (
    <Button>Click me!</Button>
  )
};

export default Component;