tag do formulário:
```bash
<form>"formulário.aqui"</form>
```
como e para onde enviar os dados preenchidos:
```bash
<form action="id.servidar.dados" method="POST">
```
área para preencher texto:
```bash
<section
 class="nome.atributo.classe">
<label for="igual.ao.id">"texto"</label>
<input type="text" name="x" id="x">
</section>
```
área para preencher com número:
```bash
<section
 class="nome.atributo.classe">
<label for="igual.ao.id">"texto"</label>
<input type="number" name="x" id="x">
</section>
```
controle deslizavel(parecido como um botão de volume:)
```bash
<section
 class="nome.atributo.classe">
<label for="igual.ao.id">"texto"</label>
<br>
<span>"texto.esquerda.espectro"</span>
<input type="range" name="x" id="x" value="igual.ao.id" min="x" max="x">
<span>"texto.direita.espectro"</span>
</section>
```
caixa de seleção:
```bash
<section
 class="nome.atributi.classe">
<span>"texto"</span>
<br>
<input type="checkbox" name="x" id="x" value="igual.ao.id">
<label for="igual.ao.id">"text"</label>
</section>
```
escolha única:
```bash
<section 
class="nome.atributo.classe">
<span>"texto"</span>
<br>
<input type="radio" name="x" id="x" value="igual.ao.id">
<label for="igual.ao.id">"texto"</label>
</section>
```
lista suspensa:
```bash
<section 
class="nome.atributo.classe">
<label for="igual.ao.id">"texto"</label>
<select name="x" id="x">
<option value="igual.ao.id">"texto"</option>
</select>
</section>
```
usuário selecione a opção desejado a partir de uma lista de opções predefinidas:
```bash
<section class="nome.atributo.classe">
<label for="igual.ao.id">"texto"</label>
<input list="x" id="x" name="igual.ao.id">
<datalist id="x">
<option value="x"></option>
<option value="x"></option>
<option value="x"></option>
</datalist>
</section>
```
área de preencher texto personalizável:
```bash
<section class="nome.atributo.classe">
<label for="igual.ao.id">"texto"</label>
<br>
<textarea id="x" name="igual.ao.id" rows="x" cols="x"></textarea>
</section>
```
botão para enviar informações ao servidor:
```bash
<section class="nome.atributo.classe">
<input type="submit" value="igual.a.type">
</section>
```