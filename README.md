# mcbroken-archive
Archive for data from [mcbroken.com](https://mcbroken.com). It updates the `mcbroken.json` file every hour.

Mirror of [this repository](https://github.com/MrFlynn/mcbroken-archive).

# How do I get historical data?

If you want to find historical data of ice cream machine failures you can dump all past reversions of the `mcbroken.json` file with the `list-revisions.sh` script.

```
$ ./list-revisions.sh mcbroken.json
```

This will create a folder called `revisions` with a separate file for each version of the file:

```
$ ls ./revisions

0001.13-Apr-2021.689154f175c488b91fa6d8fcc05d34c61bd5a9a4.mcbroken.json
0002.13-Apr-2021.73865f3df4ac11a76482d404a703d612072b4f0d.mcbroken.json
0003.13-Apr-2021.3a3d40091f8f0092a5e6f4758c7c5e0d1c93ea65.mcbroken.json
0004.13-Apr-2021.956eec0bb0978ebd6cab8381135a5722844fabc4.mcbroken.json
0005.13-Apr-2021.66becde8497ac3242c36cbacc7515f027548618b.mcbroken.json
0006.13-Apr-2021.58025c9722d735b7cc8f93eaac70e0258ebd8f8e.mcbroken.json
0007.13-Apr-2021.8b1ce44b6f541f1a0c3462a0e9f7ba0e715b15da.mcbroken.json
0008.13-Apr-2021.a0b5190b51b928c6ed3f6f67c81ec5ea0da0669f.mcbroken.json
[...]
6743.25-Oct-2020.18dbfe3a2bd5b420c7494729d90aee0d7c2d7456.mcbroken.json
6744.25-Oct-2020.08f76b1c9e1a8482f63ffab874562bc5c2fa1750.mcbroken.json
6745.25-Oct-2020.b0944da9b1f6759b130410fff6899b1c562a9797.mcbroken.json
6746.25-Oct-2020.37029998953c38bb4e1082198e6d4711abf27307.mcbroken.json
6747.25-Oct-2020.2e7d87dada1ee092be98200506a144f46fddbea1.mcbroken.json
6748.25-Oct-2020.623b9995842b68906fd2dd774b9791180dd3a2be.mcbroken.json
6749.25-Oct-2020.2b7680216927f94f476a1ba33486c440ac8ca638.mcbroken.json
6750.24-Oct-2020.596231b9fa26c466d548c12cb9262d67864f7e44.mcbroken.json
6751.24-Oct-2020.0ec8119c6099a27dc0765c17ddbcab1eab098147.mcbroken.json
6752.24-Oct-2020.16feb9d579bf7a5c192d70696d76e09dffafe7a2.mcbroken.json
```
