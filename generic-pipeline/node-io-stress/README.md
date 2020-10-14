# Node IO Stress Test

## Experiment Metadata

<table>
 <tr>
  <th> Name </th>
  <th> Description </th>
  <th> Documentation Link </th>
 </tr>
 <tr>
  <td> Node IO Stress </td>
  <td> This test the node io stress experiment which causes io stress on the Kubernetes node. The experiment aims to verify the resiliency of applications that share this disk resource for ephemeral or persistent storage purposes </td>
  <td>  <a href="https://docs.litmuschaos.io/docs/node-io-stress/"> Here </a> </td>
 </tr>
</table>

### Pipeline Runs
 

| Job ID |   Test Description         | Execution Time | Release Tag   | Test Result   |
 |---------|---------------------------| --------------|--------|--------|
 |    <a href= "https://gitlab.mayadata.io/litmuschaos/litmus-e2e/-/jobs/223819">223819</a>   |  Give IO disk stress on a node belonging to a deployment           |  Wed Oct  7 21:30:29 2020(IST)     |ci  |Failed :worried:  |