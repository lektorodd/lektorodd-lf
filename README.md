# Lektorodd-lf Format

Lite custom-format for å eksportera løysingsforlaga på bloggen til ok. pdf-ar...

> [!NOTE]
> `#` for "Del 1" og "Del 2"
> 
> `##` for "Oppgåve 1" osb
> 
> `###` for "a) løyse likning" osb  


> [!IMPORTANT]
> Inkluder
>
> ```md
> ::: {.content-hidden unless-format="html"}
> dette gjerdet
> :::
> ```
>
> rundt ting som berre skal vera med på nettsida. 

> [!IMPORTANT]
> Inkluder
>
> ```yaml
> format:
>     html: default
>     lektorodd-lf-typst:
>         output-file: FILNAMN (legg til sjølv)
> format-links:
>   - html
>   - format: lektorodd-lf-typst
>     text: "Last ned som PDF"
> 
> i yaml-header for å få det til å funka

