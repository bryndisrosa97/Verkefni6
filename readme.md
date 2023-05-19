# Verkefni 6

## Lýsing

Nú er eigandi _Bókabúðarinnar_ kátur með útlitið en hefur áhyggjur af viðhaldi á vefnum.

Loka verkefnið (í bili) er að setja upp tól og koma verkefninu fyrir á GitHub fyrir þá vefforritara sem taka við í framtíðinni.

## Útlit 
for 1200px 
![image](https://github.com/bryndisrosa97/Verkefni6/assets/61384036/989601f0-c6c1-4cb0-a2c4-0494e1a6258f)

700 px 
![image](https://github.com/bryndisrosa97/Verkefni6/assets/61384036/0c5eddd7-bba1-4758-9f50-f489853cb140)

400px 

![image](https://github.com/bryndisrosa97/Verkefni6/assets/61384036/b1187e50-315f-4863-9d9b-9662964138a0)



## Tól

Til þess að geta notað þessi tól þarf að [setja upp Node.js, sækið „Recommended For Most Users“](https://nodejs.org/en/). Eftir að þið hafið keyrt uppsetningar forrit getið þið opnað Command prompt/terminal/skel og keyrt:

```bash
> node -v
v12.18.4 # eða sú útgáfa sem þið sóttuð
> npm -v
6.14.8 # eða álíka
```



Tools notuð node-sass, browser-sync, stylelint og concurrently til að nýta Sass og geta gert breytingar sem sjást strax í vafra.

Fyrst þarf að búa til `package.json` með því að keyra `npm init` í verkefnamöppu.

Síðan þarf að sækja hvert tól með `npm install <nafn á tóli>`.


### Sass

Skipta skal CSS upp í mismunandi skrár undir `styles/`, sjá viðeigandi komment í hverju og einu skjali.

Í `styles/config.scss` skal geyma allar stillingar fyrir verkefni og nota þær á viðeigandi stöðum.

Nota skal _nesting_ en aðeins upp á eitt level.

```scss
.book {
  .title {
    // ok

    .item {
      // ekki ok, þriðja level
    }
  }
}
```

[Sjá dæm í fyrirlestri](https://github.com/vefforritun/vef1-2020/tree/master/fyrirlestrar/06/daemi/node-sass).

### Browser sync & concurrently

Þegar skipunin `npm run dev` er keyrð skal verkefnið keyra upp vefþjón með browser-sync, þýða sass skrár og fylgjast með breytingum á HTML og Sass.


### Linting

Setja skal upp stylelint með `stylelint-config-sass-guidelines` og `stylelint-config-standard`.

Þegar skipunin `npm run lint -s` er keyrð skal keyra stylelint með þessum reglum og ættu engar villur að koma fram.




## Myndir

* [Stanislav Kondratiev](https://unsplash.com/@technobulka)
* [Francesca Tirico](https://unsplash.com/@fra99)
* [Toa Heftiba](https://unsplash.com/@heftiba)
* [Andrew Neel](https://unsplash.com/@andrewtneel)
* [Christine Keller](https://unsplash.com/@christinekeller)

> Útgáfa 0.2
