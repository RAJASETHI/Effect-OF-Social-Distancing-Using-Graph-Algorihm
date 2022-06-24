<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  </head>
  <body>
    <h1>Effect-OF-Social-Distancing-Using-Graph-Algorihm</h1>
    <p>
      • Simulates the spread and extent of a disease (Covid-19) taking a virtual
      population count and their interactions and behavior into account.<br />
      • Shows result for any community spreadable disease given its infectivity
      rate. <br />• Displays the number of people infected and its
      standard deviations on the nth day of start of the pandemic in a location.
    </p>
    <img src="https://image.shutterstock.com/image-vector/spread-coronavirus-infection-infographics-covid19-260nw-1677773581.jpg" alt="covid-image">
    <br>
    <h2>Algorithm Used:</h2>
    <img src="Results/rr1.jpg" >
    <p>Modified Floyd Warshall for finding the Transitive Closure.</p>
    <br>
       <h2>Various Social Distancing Scenarios </h2>
    <img src="https://edit.org/img/blog/bvb-templates-coronavirus-business-recommendations-protocols-social-distance.jpg" height="350em">
   <p>It lists the various cases of restricted interactions among the 
    populations. These restricted cases are explained below. </p>
    <h3>Without any social distancing (T100) </h3>
    <p>It is the base case with no restrictions</p>
    <h3>With social distancing reducing contacts to 50% (T50) </h3>
    <p>The person-to-person interaction is reduced to one half the level used in T100 
      experimentations. However, the interaction with the service providers remains at the level used 
      in the business as usual level. 
      You may achieve this by performing reset of certain set values in the adjacency matrix. 
      </p>
      <h3>With social distancing reducing contacts to 33% (T33) </h3>
      <p>The person-to-person interaction is reduced to a third of the level used in T100 
        experimentations. However, the interaction with the service providers remains at the level used 
        in the business as usual level. </p>
        <h3>With social distancing reducing contacts to 50% with assigned service 
          provider (TC) </h3>
          <p>The person-to-person interaction is reduced to one half the level used in T100 
            experimentations. Further, the odd numbered service provider will only interact with the 
            persons with odd indices. Similarly, an even indexed person only gets service from a service 
            provider with even index.</p>
    <br>
    <h2>Result:</h2>
    <p>
    <img src="Results/rs1.jpg">
      <img src="Results/rs2.jpg">
      <img src="Results/rs3.jpg">
      <img src="Results/rs4.jpg">
    </p>
    <br>
    <h2>Conclusion:</h2>
    <p><ul>
        <li>Number of Infected persons decreases with limiting interactions.</li>
        <li>Restricting service provider doesn’t mean much until we restrict normal residents 
            to an extreme extent
            </li>
            <li>Faced challenges while deciding the various setting of the town, normal residents’ 
                interactions, service providers’ interactions in accordance with the total 
                population.Solved it by sampling different inputs and testing from multiple cases and got the 
                most suitable settings
                </li>
    </ul></p>
  </body>
</html>
