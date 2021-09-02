# mern-world (React)
<Router>
    <Switch>
      <Route path="/" exact>
        <Users />
      </Route>
      <Route path="/places/new" exact>
        <NewPlace />
      </Route>
      <Redirect to="/" />
    </Switch>
  </Router>
  
  Switch is used so it will only got to  <Redirect to="/" /> only if there is no path found if you do not use switch it will always go to  <Redirect to="/" />
