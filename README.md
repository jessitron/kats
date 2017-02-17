# Kats Conference 2
[Dublin, Ireland, 18 February 2017](katsconf.com)

in which I show how we might automate modification of Elm code
by writing our own Scala parser-combinator.

If you think this is cool then come talk to me in our [community Slack](https://join.atomist.com)!
or email me, whatever. jessitron at gmail

Links to stuff I used and talked about:
   * [Hello World in Elm](src/Main.elm)
   * a [demo app in Elm](https://github.com/jessitron/yow-sydney) that shows more boilerplate
   * a [picture](see-the-elm-boilerplate.png) that outlines the boilerplate for a text input in pink
   * mt [talk from CodeMesh](https://youtu.be/yFN8Y0Aoflw) where I use editors to automate Elm boilerplate
   * a [Scala project generator](https://github.com/atomist-rugs/scala-project) used in the talk
   * the parser-combinator Rug language extension we built (TODO: push it up after the talk)
   * open-source repos for [Rug](https://github.com/atomist/rug) and the [Rug CLI](https://github.com/atomist/rug-cli)
   * the [rug archive](https://github.com/jessitron/kats-rugs) containing 
      * the [change the greeting](https://github.com/jessitron/kats-rugs/blob/master/.atomist/editors/ChangeMainToPrint.rug) rug
      * the WrapFunctionBody rug [using the Scala language extension](https://github.com/jessitron/kats-rugs/blob/master/.atomist/editors/WrapFunctionBody.ts)
      * the WrapFunctionBody rug [using Microgrammars](https://github.com/jessitron/kats-rugs/blob/master/.atomist/editors/WrapFunctionBodyMicrogrammar.ts)
  
  * my [TreeNodePrinter microlibrary](https://github.com/jessitron/microlib-TreeNodePrinter)
  * more about Atomist:
     * [our website](https://atomist.com)
     * [our blog](https://the-composition.com)
     * [community Slack](https://join.atomist.com)
