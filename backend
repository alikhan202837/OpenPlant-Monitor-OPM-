from opcua import Client

client = Client("opc.tcp://localhost:4840")
client.connect()

node = client.get_node("ns=2;i=2")
print("Value:", node.get_value())

client.disconnect()
