This chart makes a very basic [strongdm](https://www.strongdm.com/) gateway. https://www.strongdm.com/docs/admin-guide/gateways/

To install the gateway include a defined node port and the gateway token as values.

```
helm upgrade strongdm-relay ./strongdm-relay --set service.nodePort=31125 --set sdm.gateway.token=<TOKEN>
```
