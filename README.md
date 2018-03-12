# Conditional-flow
Conditional flow using choice router. Choice router evaluates the message based on the expression and routes it accordingly to different routing options.
In this first we set a query parameter 'route' using flow vars, then we set the condition in choice router so that when we pass the query parameter=true then it routes to first routing option and prints the payload present in that, otherwise it routes to default routing option and prints the payload present in default block.
