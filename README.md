# terraform-aws-vpc-setup

<h1>Practice Creating and Deploying a Complete VPC</h1>
<p><strong>Components:</strong></p>
<ul>
  <li>2 public subnets, 2 private subnets</li>
  <li>Public route table, private route table</li>
  <li>1 Internet Gateway, 1 NAT Gateway</li>
  <li>Verify the created resources</li>
</ul>

<h2>Steps:</h2>
<ol>
  <li>
    <strong>Networking Module:</strong>
    <ul>
      <li>Create and deploy the VPC with the specified components.</li>
    </ul>
  </li>
  <li>
    <strong>Security and Compute Modules:</strong>
    <ul>
      <li>Deploy these modules after the networking module is successfully deployed.</li>
      <li>The Security Group should receive the VPC ID from the networking module output.</li>
      <li>The EC2 instance should receive the Security Group ID from the security module output.</li>
    </ul>
  </li>
</ol>
