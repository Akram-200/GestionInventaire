<h1>Gestion d’inventaire – C# & SQL Server</h1>
<hr>

<h2>Description</h2>
<hr>
<p>
Application simple de gestion d’inventaire développée en <strong>C#</strong> avec
<strong>SQL Server</strong>.
Projet académique réalisé dans le cadre du
<strong>DEC Techniques de l’informatique (Collège LaSalle)</strong>.
</p>

<h2>Fonctionnalités</h2>
<hr>
<ul>
  <li>Ajouter un produit</li>
  <li>Modifier un produit</li>
  <li>Supprimer un produit</li>
  <li>Afficher la liste des produits</li>
</ul>

<h2>Technologies utilisées</h2>
<hr>
<ul>
  <li>C# (WinForms)</li>
  <li>SQL Server</li>
  <li>ADO.NET</li>
  <li>Visual Studio</li>
</ul>

<h2>Structure du projet (prévue)</h2>
<hr>
<ul>
  <li><strong>Models/</strong> : classes métier (ex. Produit)</li>
  <li><strong>Data/</strong> : connexion et accès à la base de données</li>
  <li><strong>Database/</strong> : scripts SQL</li>
  <li><strong>Screenshots/</strong> : captures d’écran de l’application</li>
</ul>

<h2>Base de données</h2>
<hr>

<h3>Table : Produits</h3>
<ul>
  <li><strong>Id</strong> (int, clé primaire)</li>
  <li><strong>Nom</strong> (varchar)</li>
  <li><strong>Quantite</strong> (int)</li>
  <li><strong>Prix</strong> (decimal)</li>
</ul>

<p>
Le script de création de la base de données se trouve dans :
<code>Database/script.sql</code>
</p>

<h2>Objectif pédagogique</h2>
<hr>
<ul>
  <li>Pratiquer les opérations <strong>CRUD</strong></li>
  <li>Comprendre la connexion à une base de données avec <strong>ADO.NET</strong></li>
  <li>Structurer un projet <strong>C#</strong> de façon claire</li>
</ul>

<h2>Captures d’écran</h2>
<hr>
<ul>
  <li>Interface d’ajout de produit</li>
  <li>Liste des produits</li>
</ul>
