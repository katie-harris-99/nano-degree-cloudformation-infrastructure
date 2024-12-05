# CD12352 - Infrastructure as Code Project Solution
# Katherine Harris
Project can be accessed here: http://udagra-WebAp-XdoUupb9kvPr-334886989.us-east-1.elb.amazonaws.com

## Spin up instructions
Run the following in orer to first spin up the network resources and then the servers
`./create.sh network network.yml network-parameters.json`

`./create.sh udagram udagram.yml udagram-parameters.json`

## Tear down instructions
Run the following ino order to tear down the stacks
`./delete.sh network'`

`./delete.sh udagram`
