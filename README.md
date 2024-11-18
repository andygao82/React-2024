React Learning 2024


Old Lifecycle
1. Initial Phase: 
  a. constructor()
  b. componentWillMount()
  c. render()
  d. componentDidMount() ====> most useful, in this hook, you can do something like initialization. e.g. setInterval, request, subscription.

2. Update Phase:
  a. shouldComponentUpdate()
  b. componentWillUpdate()
  c. render()
  d. componentDidUpdate() ====> most useful, in this hook, you can do something like finish. e.g. turn off setInterval, cancel subscription

3. Dismount Phase:
  a. componentWillDismount()