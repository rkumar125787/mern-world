# mern-world (React)
```javascript
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
```
###### switch is used to restrict path if path is not find then only it will goto  **Redirect**  without swtich it will go to **Redirect** everytime .