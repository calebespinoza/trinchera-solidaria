PUBLISH ON GITHUB PAGES WITH www.trincherasolidaria.org.bo

1. On github.com: New repository, name it "trinchera-solidaria", Public.
2. Add file > Upload files: upload EVERYTHING in this folder (index.html, kermesse.html, contenido.json, support.js, CNAME, .nojekyll and the assets folder). Commit.
3. Repo > Settings > Pages > Source: "Deploy from a branch", Branch: main, folder / (root). Save.
4. In your domain's DNS panel, create:
   - CNAME | host: www | value: YOUR-USERNAME.github.io
   - For the bare domain (trincherasolidaria.org.bo), create 4 A records pointing to:
     185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
5. Settings > Pages > Custom domain: www.trincherasolidaria.org.bo > Save. Once DNS propagates (minutes to hours), check "Enforce HTTPS".

EDITING CONTENT: edit contenido.json on GitHub (pencil icon) and Commit. The site updates in about 1 minute.
Note: the #admin editor only saves in the browser of whoever uses it. To publish changes, download the JSON from the editor and upload it as contenido.json.
