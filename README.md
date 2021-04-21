# FedExp
Federated algorithm with an exponential weighted average approach.

<ul>
  <li>Our objective is to refine the neural network of a node by considering it as a linear combination of neural networks of the other nodes, weighed by the statistical similarity of the data available at these nodes.</li>
  <li>We thus require a simple method to weigh the neural networks learnt by various nodes in the network.</li>
  <li>To this cause, we find that exponential weighted average is one such simple method which does the job. It is in particular suitable for online learning scenario where the neural network needs to adapt itself quickly to the incoming data.</li>
  <li>We have observed that though FL in online scenario is studied, most of these studies provide equal weight to the nodes in the network, rather than considering a weighted average approach.</li>
  <li>We note here that <a href="https://github.com/ksanu1998/FedExp">Fed-Exp</a> is ‘lighter’ communication and computation-wise when compared to <a href="https://github.com/ksanu1998/OmniFedge">Omni-Fedge<a/>, our previous work.</li>
</ul>
