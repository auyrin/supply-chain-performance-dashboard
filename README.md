# supply-chain-performance-dashboard
here i create a dashboard that tracks the performance of the supply chain of an online store.
## problem statement
our supply chain company is having issues; our key customers are not renewing their contracts with us. we don't really know our customer satisfaction level, and would want to be able to track our performance. management decides to deploy analytics for service level tracking.
## metrics displayed
- Volume fill rate (VOFR) -> the total quantity they are able to ship for a customer per order
- Line fill rate (LFR) -> how many lines they shipped out of the total lines ordered.
- On time (OT) ->  It determines if an order is delivered as per the agreed time with the customer.
- In full (IF) -> It determines if an order is delivered in full as per the requested quantity by the customer.
- On time in full (OTIF) -> it determines if an order is delivered BOTH in full and On Time as per the customer order request.
## requests from manager
- display the  OT, IF, OTIF, VOFR, LFR percentages for each given day vs our targets.
- split these metrics for each city and customer. also display them vs our targets
- show the VOFR and LFR for all our products. also display their sparklines.
- show the trend of these metrics vs our targets. create a button so i can switch between metrics.
