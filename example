import * as React from "react";
import "./styles.css";
import "react-step-progress-bar/styles.css";
import { ProgressBar, Step } from "react-step-progress-bar";

export default function App() {
  return (
    <div className="App">
      <h1>Hello CodeSandbox</h1>
      <h2>Start editing to see some magic happen!</h2>
      <ProgressBar
        percent={19}
        // width={500}
        filledBackground="linear-gradient(to right, #fefb72, #f0bb31)"
      >


        <Step transition="scale">
          {({ accomplished }: any) => (
            <h1>test</h1>
          )}
        </Step>


        
        <Step transition="scale">
          {({ accomplished }: any) => (
            <h3>step 2</h3>
          )}
        </Step>


        <Step transition="scale">
          {({ accomplished }: any) => (
            <img
              alt="img"
              style={{ filter: `grayscale(${accomplished ? 0 : 80}%)` }}
              width="100"
              src="https://orig00.deviantart.net/493a/f/2017/095/5/4/raichu_icon_by_pokemonshuffle_icons-db4ryym.png"
            />
          )}
        </Step>


      </ProgressBar>
    </div>
  );
}
