# INTEGRA — Site GitHub Pages

Publique todos os arquivos deste pacote na raiz de um repositório GitHub, mantendo as pastas `assets` e `assets/img`.

Em **Settings → Pages**, escolha **Deploy from a branch**, branch **main**, pasta **/(root)**.

## Configurar inscrição

No arquivo `index.html`, encontre o trecho:

```html
<span class="btn disabled" aria-disabled="true">Formulário em breve</span>
```

Substitua por:

```html
<a class="btn lime" href="COLE_AQUI_O_LINK_DO_GOOGLE_FORMS" target="_blank" rel="noopener noreferrer">Inscrever-se pelo Google Forms ↗</a>
```

## Atualizar os avisos

Na seção `id="avisos"` de `index.html`, substitua os três textos **A definir** por sala/local, dias e horário confirmados. Ajuste a descrição da carga horária se a programação final for diferente.

A foto do coordenador está em `assets/img/cassius.jpg`. Links para a página pessoal, a disciplina e o WhatsApp já estão configurados.
