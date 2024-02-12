campo para preenchimento obrigatório:
```bash
<form action="id.local.dados" method="GET">
<label for="igual.ao.id">"texto"</label>
<br>
<input type="number" name="igual.ao.id" id="x" required>
<br>
<input type="submit" id="x" value="x">
</form>
```
escolher número entre x e y:
```bash
<form action="id.local.dados" method="GET">
<label for="igual.ao.id">"texto"</label>
<br>
<input type="number" name="igual.ao.id" id="x" min="x" max="x" required>
<br>
<input type="submit" id="x" value="x">
</form>
  ```
nome e senha:
```bash
<form action="id.local.dados" method="GET">
<label for="igual.ao.id">Username:</label>
<br>
<input id="x" name="igual.ao.id" type="text" required pattern="[a-zA-Z0-9]+" >
<br>
<label for="igual.ao.id">Password:</label>
<br>
<input id="x" name="igual.aoid" type="password" required minlength="8" maxlength="15">
<br>
<input type="submit" value="Submit">
</form>
