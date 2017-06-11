<h1>Stanley algorithm demo package</h1>
<br>
<p><li>This package implements stanley algorithm with simple demo in STDR simulator and GAZEBO simulator.</li>
<br>
<p><li>The driver has been tested with ROS Kinetic on Ubuntu 16.04 64-bit.</li>
<br>
<h3>Packages required</h3>
<ul style="list-style-type:circle">
<li> <a href="https://github.com/br5555/stanley">Stanley algoirthm </a> </li>
<li> <a href="https://github.com/allenh1/p2os">Gazebo model of Pioneer P3-DX </a> </li>
</ul>
<br>
<h3>Before running launch file</h3>
<ul style="list-style-type:circle">
<p><li>robotName.sh</li>
</ul>
<br>
<p>The team of Stanford  implemented the velocity and steering controllers
separately for its vehicle “Stanley” at the DARPA Grand Challenge. The velocity
control is implemented as a PI controller, while the steering angle is computed by a
nonlinear feedback function of the cross-track error, which is known as the “Stanley
method.” The performance of this controller degrades seriously at higher speeds.</p>
<br>
<h3>stanleySTDR.launch contains:</h3>

  <ol>
  <li>pureStanley.launch(running stanley algoritham)</li>
  <li >move_base_stdr_sim.launch: </li>
    <ul>
        <li>stdr_simulator </li>
         <li>sets move_base parameters </li>
          <li>rviz </li>
    </ul>
  </ol>
<br>
<h3>p3dx-gazebo-empty-stanley.launch contains:</h3>

  <ol>
  <li>lattice planner</li>
  <li>pureStanley.launch</li>
  <li>gazebo simulator</li>
  <li>urdf p3-dx model</li>
  <li>rviz</li>
  </ol>

 


