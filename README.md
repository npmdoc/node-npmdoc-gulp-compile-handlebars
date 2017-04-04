# api documentation for  [gulp-compile-handlebars (v0.6.1)](https://github.com/kaanon/gulp-compile-handlebars)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-compile-handlebars.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-compile-handlebars) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-compile-handlebars.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-compile-handlebars)
#### Compile Handlebars templates to file - gulp plugin

[![NPM](https://nodei.co/npm/gulp-compile-handlebars.png?downloads=true)](https://www.npmjs.com/package/gulp-compile-handlebars)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-compile-handlebars/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-gulp-compile-handlebars_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-compile-handlebars/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-compile-handlebars/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-compile-handlebars/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kaanon MacFarlane",
        "email": "kaanonm@gmail.com",
        "url": "http://kaanon.com"
    },
    "bugs": {
        "url": "https://github.com/kaanon/gulp-compile-handlebars/issues"
    },
    "dependencies": {
        "gulp-util": "^3.0.3",
        "handlebars": ">=3.0.0",
        "through2": "^0.6.3"
    },
    "description": "Compile Handlebars templates to file - gulp plugin",
    "devDependencies": {
        "mocha": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "9cc1d9cb951105dfae530928d2a904a14d74c5d3",
        "tarball": "https://registry.npmjs.org/gulp-compile-handlebars/-/gulp-compile-handlebars-0.6.1.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "8f709fa50e4a0a8940af2df08bb00020dda3ddb8",
    "homepage": "https://github.com/kaanon/gulp-compile-handlebars",
    "keywords": [
        "gulp",
        "handlebars",
        "gulp-plugin",
        "template",
        "compile",
        "html",
        "rendering"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "kaanon",
            "email": "kaanonm@gmail.com"
        }
    ],
    "name": "gulp-compile-handlebars",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kaanon/gulp-compile-handlebars.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "version": "0.6.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module gulp-compile-handlebars](#apidoc.module.gulp-compile-handlebars)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.Compiler ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.HandlebarsEnvironment (helpers, partials, decorators)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.JavaScriptCompiler ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.PrintVisitor ()](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.SafeString (string)](#apidoc.element.gulp-compile-handlebars.Handlebars.SafeString)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.Visitor ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor)
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.Compiler.prototype
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.HandlebarsEnvironment.prototype
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.JavaScriptCompiler.prototype
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.PrintVisitor.prototype
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.SafeString.prototype
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.Utils
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.VM
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.Visitor.prototype
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.decorators
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.helpers
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.logger

#### [module gulp-compile-handlebars.Handlebars](#apidoc.module.gulp-compile-handlebars.Handlebars)
1.  boolean <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>__esModule
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>Compiler ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>Exception (message, node)](#apidoc.element.gulp-compile-handlebars.Handlebars.Exception)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>HandlebarsEnvironment (helpers, partials, decorators)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>JavaScriptCompiler ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>PrintVisitor ()](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>SafeString (string)](#apidoc.element.gulp-compile-handlebars.Handlebars.SafeString)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>Visitor ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>compile (input, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.compile)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>create ()](#apidoc.element.gulp-compile-handlebars.Handlebars.create)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>createFrame (object)](#apidoc.element.gulp-compile-handlebars.Handlebars.createFrame)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>escapeExpression (string)](#apidoc.element.gulp-compile-handlebars.Handlebars.escapeExpression)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>log (level)](#apidoc.element.gulp-compile-handlebars.Handlebars.log)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>noConflict ()](#apidoc.element.gulp-compile-handlebars.Handlebars.noConflict)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>parse (input, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.parse)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>precompile (input, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.precompile)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>print (ast)](#apidoc.element.gulp-compile-handlebars.Handlebars.print)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>template (spec)](#apidoc.element.gulp-compile-handlebars.Handlebars.template)
1.  number <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>COMPILER_REVISION
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>AST
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>Parser
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>REVISION_CHANGES
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>Utils
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>VM
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>decorators
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>default
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>helpers
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>logger
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>partials
1.  string <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>VERSION

#### [module gulp-compile-handlebars.Handlebars.Compiler](#apidoc.module.gulp-compile-handlebars.Handlebars.Compiler)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>Compiler ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.Compiler)

#### [module gulp-compile-handlebars.Handlebars.Compiler.prototype](#apidoc.module.gulp-compile-handlebars.Handlebars.Compiler.prototype)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>BlockStatement (block)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.BlockStatement)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>BooleanLiteral (bool)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.BooleanLiteral)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>CommentStatement ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.CommentStatement)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>ContentStatement (content)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.ContentStatement)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>Decorator (decorator)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.Decorator)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>DecoratorBlock (decorator)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.DecoratorBlock)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>Hash (hash)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.Hash)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>MustacheStatement (mustache)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.MustacheStatement)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>NullLiteral ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.NullLiteral)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>NumberLiteral (number)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.NumberLiteral)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>PartialBlockStatement (partialBlock)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.PartialBlockStatement)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>PartialStatement (partial)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.PartialStatement)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>PathExpression (path)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.PathExpression)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>Program (program)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.Program)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>StringLiteral (string)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.StringLiteral)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>SubExpression (sexpr)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.SubExpression)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>UndefinedLiteral ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.UndefinedLiteral)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>accept (node)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.accept)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>addDepth (depth)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.addDepth)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>ambiguousSexpr (sexpr, program, inverse)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.ambiguousSexpr)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>blockParamIndex (name)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.blockParamIndex)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>classifySexpr (sexpr)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.classifySexpr)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>compile (program, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.compile)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>compileProgram (program)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.compileProgram)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>compiler ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.compiler)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>equals (other)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.equals)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>helperSexpr (sexpr, program, inverse)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.helperSexpr)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>opcode (name)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.opcode)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>pushParam (val)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.pushParam)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>pushParams (params)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.pushParams)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>setupFullMustacheParams (sexpr, program, inverse, omitEmpty)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.setupFullMustacheParams)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>simpleSexpr (sexpr)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.simpleSexpr)
1.  number <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>guid

#### [module gulp-compile-handlebars.Handlebars.HandlebarsEnvironment](#apidoc.module.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>HandlebarsEnvironment (helpers, partials, decorators)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.HandlebarsEnvironment)

#### [module gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype](#apidoc.module.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.</span>constructor (helpers, partials, decorators)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.</span>log (level)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.log)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.</span>registerDecorator (name, fn)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.registerDecorator)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.</span>registerHelper (name, fn)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.registerHelper)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.</span>registerPartial (name, partial)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.registerPartial)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.</span>unregisterDecorator (name)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.unregisterDecorator)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.</span>unregisterHelper (name)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.unregisterHelper)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.</span>unregisterPartial (name)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.unregisterPartial)
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.</span>logger

#### [module gulp-compile-handlebars.Handlebars.JavaScriptCompiler](#apidoc.module.gulp-compile-handlebars.Handlebars.JavaScriptCompiler)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>JavaScriptCompiler ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.JavaScriptCompiler)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.</span>isValidJavaScriptVariableName (name)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.isValidJavaScriptVariableName)
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.</span>RESERVED_WORDS

#### [module gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype](#apidoc.module.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>aliasable (name)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.aliasable)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>ambiguousBlockValue ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.ambiguousBlockValue)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>append ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.append)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>appendContent (content)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.appendContent)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>appendEscaped ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.appendEscaped)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>appendToBuffer (source, location, explicit)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.appendToBuffer)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>assignToHash (key)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.assignToHash)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>blockValue (name)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.blockValue)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>compile (environment, options, context, asObject)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.compile)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>compileChildren (environment, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.compileChildren)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>compiler ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.compiler)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>compilerInfo ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.compilerInfo)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>contextName (context)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.contextName)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>createFunctionContext (asObject)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.createFunctionContext)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>depthedLookup (name)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.depthedLookup)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>emptyHash (omitEmpty)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.emptyHash)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>flushInline ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.flushInline)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>getContext (depth)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.getContext)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>incrStack ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.incrStack)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>initializeBuffer ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.initializeBuffer)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>invokeAmbiguous (name, helperCall)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.invokeAmbiguous)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>invokeHelper (paramSize, name, isSimple)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.invokeHelper)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>invokeKnownHelper (paramSize, name)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.invokeKnownHelper)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>invokePartial (isDynamic, name, indent)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.invokePartial)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>isInline ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.isInline)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>lookupBlockParam (blockParamId, parts)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.lookupBlockParam)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>lookupData (depth, parts, strict)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.lookupData)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>lookupOnContext (parts, falsy, strict, scoped)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.lookupOnContext)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>matchExistingProgram (child)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.matchExistingProgram)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>mergeSource (varDeclarations)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.mergeSource)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>nameLookup (parent, name)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.nameLookup)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>objectLiteral (obj)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.objectLiteral)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>popHash ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.popHash)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>popStack (wrapped)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.popStack)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>preamble ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.preamble)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>programExpression (guid)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.programExpression)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>push (expr)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.push)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>pushContext ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushContext)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>pushHash ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushHash)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>pushId (type, name, child)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushId)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>pushLiteral (value)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushLiteral)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>pushProgram (guid)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushProgram)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>pushSource (source)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushSource)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>pushStackLiteral (item)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushStackLiteral)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>pushString (string)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushString)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>pushStringParam (string, type)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushStringParam)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>quotedString (str)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.quotedString)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>registerDecorator (paramSize, name)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.registerDecorator)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>replaceStack (callback)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.replaceStack)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>resolvePath (type, parts, i, falsy, strict)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.resolvePath)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>resolvePossibleLambda ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.resolvePossibleLambda)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>setupHelper (paramSize, name, blockHelper)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.setupHelper)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>setupHelperArgs (helper, paramSize, params, useRegister)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.setupHelperArgs)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>setupParams (helper, paramSize, params)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.setupParams)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>topStack ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.topStack)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>topStackName ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.topStackName)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>useRegister (name)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.useRegister)

#### [module gulp-compile-handlebars.Handlebars.PrintVisitor](#apidoc.module.gulp-compile-handlebars.Handlebars.PrintVisitor)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>PrintVisitor ()](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.PrintVisitor)

#### [module gulp-compile-handlebars.Handlebars.PrintVisitor.prototype](#apidoc.module.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>BlockStatement (block)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.BlockStatement)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>BooleanLiteral (bool)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.BooleanLiteral)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>CommentStatement (comment)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.CommentStatement)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>ContentStatement (content)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.ContentStatement)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>Decorator (mustache)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.Decorator)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>DecoratorBlock (block)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.DecoratorBlock)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>Hash (hash)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.Hash)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>HashPair (pair)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.HashPair)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>MustacheStatement (mustache)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.MustacheStatement)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>NullLiteral ()](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.NullLiteral)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>NumberLiteral (number)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.NumberLiteral)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>PartialBlockStatement (partial)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.PartialBlockStatement)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>PartialStatement (partial)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.PartialStatement)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>PathExpression (id)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.PathExpression)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>Program (program)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.Program)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>StringLiteral (string)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.StringLiteral)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>SubExpression (sexpr)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.SubExpression)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>UndefinedLiteral ()](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.UndefinedLiteral)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>pad (string)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.pad)
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>parents

#### [module gulp-compile-handlebars.Handlebars.SafeString](#apidoc.module.gulp-compile-handlebars.Handlebars.SafeString)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>SafeString (string)](#apidoc.element.gulp-compile-handlebars.Handlebars.SafeString.SafeString)

#### [module gulp-compile-handlebars.Handlebars.SafeString.prototype](#apidoc.module.gulp-compile-handlebars.Handlebars.SafeString.prototype)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.SafeString.prototype.</span>toHTML ()](#apidoc.element.gulp-compile-handlebars.Handlebars.SafeString.prototype.toHTML)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.SafeString.prototype.</span>toString ()](#apidoc.element.gulp-compile-handlebars.Handlebars.SafeString.prototype.toString)

#### [module gulp-compile-handlebars.Handlebars.Utils](#apidoc.module.gulp-compile-handlebars.Handlebars.Utils)
1.  boolean <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Utils.</span>__esModule
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Utils.</span>appendContextPath (contextPath, id)](#apidoc.element.gulp-compile-handlebars.Handlebars.Utils.appendContextPath)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Utils.</span>blockParams (params, ids)](#apidoc.element.gulp-compile-handlebars.Handlebars.Utils.blockParams)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Utils.</span>createFrame (object)](#apidoc.element.gulp-compile-handlebars.Handlebars.Utils.createFrame)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Utils.</span>escapeExpression (string)](#apidoc.element.gulp-compile-handlebars.Handlebars.Utils.escapeExpression)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Utils.</span>extend (obj)](#apidoc.element.gulp-compile-handlebars.Handlebars.Utils.extend)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Utils.</span>indexOf (array, value)](#apidoc.element.gulp-compile-handlebars.Handlebars.Utils.indexOf)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Utils.</span>isArray ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Utils.isArray)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Utils.</span>isEmpty (value)](#apidoc.element.gulp-compile-handlebars.Handlebars.Utils.isEmpty)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Utils.</span>isFunction (value)](#apidoc.element.gulp-compile-handlebars.Handlebars.Utils.isFunction)

#### [module gulp-compile-handlebars.Handlebars.VM](#apidoc.module.gulp-compile-handlebars.Handlebars.VM)
1.  boolean <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.VM.</span>__esModule
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.VM.</span>checkRevision (compilerInfo)](#apidoc.element.gulp-compile-handlebars.Handlebars.VM.checkRevision)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.VM.</span>invokePartial (partial, context, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.VM.invokePartial)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.VM.</span>noop ()](#apidoc.element.gulp-compile-handlebars.Handlebars.VM.noop)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.VM.</span>resolvePartial (partial, context, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.VM.resolvePartial)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.VM.</span>template (templateSpec, env)](#apidoc.element.gulp-compile-handlebars.Handlebars.VM.template)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.VM.</span>wrapProgram (container, i, fn, data, declaredBlockParams, blockParams, depths)](#apidoc.element.gulp-compile-handlebars.Handlebars.VM.wrapProgram)

#### [module gulp-compile-handlebars.Handlebars.Visitor](#apidoc.module.gulp-compile-handlebars.Handlebars.Visitor)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>Visitor ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.Visitor)

#### [module gulp-compile-handlebars.Handlebars.Visitor.prototype](#apidoc.module.gulp-compile-handlebars.Handlebars.Visitor.prototype)
1.  boolean <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>mutating
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>BlockStatement (block)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.BlockStatement)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>BooleanLiteral ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.BooleanLiteral)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>CommentStatement ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.CommentStatement)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>ContentStatement ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.ContentStatement)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>Decorator (mustache)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.Decorator)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>DecoratorBlock (block)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.DecoratorBlock)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>Hash (hash)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.Hash)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>HashPair (pair)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.HashPair)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>MustacheStatement (mustache)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.MustacheStatement)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>NullLiteral ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.NullLiteral)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>NumberLiteral ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.NumberLiteral)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>PartialBlockStatement (partial)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.PartialBlockStatement)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>PartialStatement (partial)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.PartialStatement)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>PathExpression ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.PathExpression)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>Program (program)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.Program)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>StringLiteral ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.StringLiteral)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>SubExpression (mustache)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.SubExpression)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>UndefinedLiteral ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.UndefinedLiteral)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>accept (object)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.accept)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>acceptArray (array)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.acceptArray)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>acceptKey (node, name)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.acceptKey)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>acceptRequired (node, name)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.acceptRequired)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>constructor ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.constructor)

#### [module gulp-compile-handlebars.Handlebars.decorators](#apidoc.module.gulp-compile-handlebars.Handlebars.decorators)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.decorators.</span>inline (fn, props, container, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.decorators.inline)

#### [module gulp-compile-handlebars.Handlebars.helpers](#apidoc.module.gulp-compile-handlebars.Handlebars.helpers)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.helpers.</span>blockHelperMissing (context, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.helpers.blockHelperMissing)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.helpers.</span>each (context, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.helpers.each)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.helpers.</span>helperMissing ()](#apidoc.element.gulp-compile-handlebars.Handlebars.helpers.helperMissing)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.helpers.</span>if (conditional, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.helpers.if)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.helpers.</span>log ()](#apidoc.element.gulp-compile-handlebars.Handlebars.helpers.log)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.helpers.</span>lookup (obj, field)](#apidoc.element.gulp-compile-handlebars.Handlebars.helpers.lookup)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.helpers.</span>unless (conditional, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.helpers.unless)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.helpers.</span>with (context, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.helpers.with)

#### [module gulp-compile-handlebars.Handlebars.logger](#apidoc.module.gulp-compile-handlebars.Handlebars.logger)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.logger.</span>log (level)](#apidoc.element.gulp-compile-handlebars.Handlebars.logger.log)
1.  [function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.logger.</span>lookupLevel (level)](#apidoc.element.gulp-compile-handlebars.Handlebars.logger.lookupLevel)
1.  object <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.logger.</span>methodMap
1.  string <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.logger.</span>level



# <a name="apidoc.module.gulp-compile-handlebars"></a>[module gulp-compile-handlebars](#apidoc.module.gulp-compile-handlebars)

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.Compiler ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler)
- description and source-code
```javascript
function Compiler() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.HandlebarsEnvironment (helpers, partials, decorators)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment)
- description and source-code
```javascript
function HandlebarsEnvironment(helpers, partials, decorators) {
  this.helpers = helpers || {};
  this.partials = partials || {};
  this.decorators = decorators || {};

  _helpers.registerDefaultHelpers(this);
  _decorators.registerDefaultDecorators(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.JavaScriptCompiler ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler)
- description and source-code
```javascript
function JavaScriptCompiler() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.PrintVisitor ()](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor)
- description and source-code
```javascript
function PrintVisitor() {
  this.padding = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.SafeString"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.SafeString (string)](#apidoc.element.gulp-compile-handlebars.Handlebars.SafeString)
- description and source-code
```javascript
function SafeString(string) {
  this.string = string;
}
```
- example usage
```shell
...

## handlebars.Handlebars

You can access the Handlebars library from the 'handlebars.Handlebars' property.

'''js
var handlebars = require('gulp-compile-handlebars');
var safestring = new handlebars.Handlebars.SafeString('<strong>HELLO! KAANON</strong>');
'''

## handlebars.Handlebars

You can access the Handlebars library from the 'handlebars.Handlebars' property.

'''js
...
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.</span>Handlebars.Visitor ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor)
- description and source-code
```javascript
function Visitor() {
  this.parents = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-compile-handlebars.Handlebars"></a>[module gulp-compile-handlebars.Handlebars](#apidoc.module.gulp-compile-handlebars.Handlebars)

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>Compiler ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler)
- description and source-code
```javascript
function Compiler() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Exception"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>Exception (message, node)](#apidoc.element.gulp-compile-handlebars.Handlebars.Exception)
- description and source-code
```javascript
function Exception(message, node) {
  var loc = node && node.loc,
      line = undefined,
      column = undefined;
  if (loc) {
    line = loc.start.line;
    column = loc.start.column;

    message += ' - ' + line + ':' + column;
  }

  var tmp = Error.prototype.constructor.call(this, message);

  // Unfortunately errors are not enumerable in Chrome (at least), so 'for prop in tmp' doesn't work.
  for (var idx = 0; idx < errorProps.length; idx++) {
    this[errorProps[idx]] = tmp[errorProps[idx]];
  }

<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (Error.captureStackTrace) {
    Error.captureStackTrace(this, Exception);
  }

  try {
    if (loc) {
      this.lineNumber = line;

      // Work around issue under safari where we can't directly set the column value
      /* istanbul ignore next */
      if (Object.defineProperty) {
        Object.defineProperty(this, 'column', { value: column });
      } else {
        this.column = column;
      }
    }
  } catch (nop) {
    /* Ignore if the browser is very particular */
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>HandlebarsEnvironment (helpers, partials, decorators)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment)
- description and source-code
```javascript
function HandlebarsEnvironment(helpers, partials, decorators) {
  this.helpers = helpers || {};
  this.partials = partials || {};
  this.decorators = decorators || {};

  _helpers.registerDefaultHelpers(this);
  _decorators.registerDefaultDecorators(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>JavaScriptCompiler ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler)
- description and source-code
```javascript
function JavaScriptCompiler() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>PrintVisitor ()](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor)
- description and source-code
```javascript
function PrintVisitor() {
  this.padding = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.SafeString"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>SafeString (string)](#apidoc.element.gulp-compile-handlebars.Handlebars.SafeString)
- description and source-code
```javascript
function SafeString(string) {
  this.string = string;
}
```
- example usage
```shell
...

## handlebars.Handlebars

You can access the Handlebars library from the 'handlebars.Handlebars' property.

'''js
var handlebars = require('gulp-compile-handlebars');
var safestring = new handlebars.Handlebars.SafeString('<strong>HELLO! KAANON</strong>');
'''

## handlebars.Handlebars

You can access the Handlebars library from the 'handlebars.Handlebars' property.

'''js
...
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>Visitor ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor)
- description and source-code
```javascript
function Visitor() {
  this.parents = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.compile"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>compile (input, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.compile)
- description and source-code
```javascript
compile = function (input, options) {
  return _handlebarsCompilerCompiler.compile(input, options, hb);
}
```
- example usage
```shell
...
				mockPartials(fileContents);
			}

			// Enable gulp-data usage, Extend default data with data from file.data
			if(file.data){
				_data = extend(_data, file.data);
			}
			var template = Handlebars.compile(fileContents, options.compile);
			file.contents = new Buffer(template(_data));
		} catch (err) {
			this.emit('error', new gutil.PluginError('gulp-compile-handlebars', err));
		}

		this.push(file);
		cb();
...
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.create"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>create ()](#apidoc.element.gulp-compile-handlebars.Handlebars.create)
- description and source-code
```javascript
function create() {
  var hb = _create();

  hb.compile = function (input, options) {
    return _handlebarsCompilerCompiler.compile(input, options, hb);
  };
  hb.precompile = function (input, options) {
    return _handlebarsCompilerCompiler.precompile(input, options, hb);
  };

  hb.AST = _handlebarsCompilerAst2['default'];
  hb.Compiler = _handlebarsCompilerCompiler.Compiler;
  hb.JavaScriptCompiler = _handlebarsCompilerJavascriptCompiler2['default'];
  hb.Parser = _handlebarsCompilerBase.parser;
  hb.parse = _handlebarsCompilerBase.parse;

  return hb;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.createFrame"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>createFrame (object)](#apidoc.element.gulp-compile-handlebars.Handlebars.createFrame)
- description and source-code
```javascript
function createFrame(object) {
  var frame = extend({}, object);
  frame._parent = object;
  return frame;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.escapeExpression"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>escapeExpression (string)](#apidoc.element.gulp-compile-handlebars.Handlebars.escapeExpression)
- description and source-code
```javascript
function escapeExpression(string) {
  if (typeof string !== 'string') {
    // don't escape SafeStrings, since they're already safe
    if (string && string.toHTML) {
      return string.toHTML();
    } else if (string == null) {
      return '';
    } else if (!string) {
      return string + '';
    }

    // Force a string conversion as this will be done by the append regardless and
    // the regex test will do this transparently behind the scenes, causing issues if
    // an object's to string has escaped characters in it.
    string = '' + string;
  }

  if (!possible.test(string)) {
    return string;
  }
  return string.replace(badChars, escapeChar);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.log"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>log (level)](#apidoc.element.gulp-compile-handlebars.Handlebars.log)
- description and source-code
```javascript
function log(level) {
  level = logger.lookupLevel(level);

  if (typeof console !== 'undefined' && logger.lookupLevel(logger.level) <= level) {
    var method = logger.methodMap[level];
    if (!console[method]) {
      // eslint-disable-line no-console
      method = 'log';
    }

    for (var _len = arguments.length, message = Array(_len > 1 ? _len - 1 : 0), _key = 1; _key < _len; _key++) {
      message[_key - 1] = arguments[_key];
    }

    console[method].apply(console, message); // eslint-disable-line no-console
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.noConflict"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>noConflict ()](#apidoc.element.gulp-compile-handlebars.Handlebars.noConflict)
- description and source-code
```javascript
noConflict = function () {
  if (root.Handlebars === Handlebars) {
    root.Handlebars = $Handlebars;
  }
  return Handlebars;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.parse"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>parse (input, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.parse)
- description and source-code
```javascript
function parse(input, options) {
  // Just return if an already-compiled AST was passed in.
  if (input.type === 'Program') {
    return input;
  }

  _parser2['default'].yy = yy;

  // Altering the shared object here, but this is ok as parser is a sync operation
  yy.locInfo = function (locInfo) {
    return new yy.SourceLocation(options && options.srcName, locInfo);
  };

  var strip = new _whitespaceControl2['default'](options);
  return strip.accept(_parser2['default'].parse(input));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.precompile"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>precompile (input, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.precompile)
- description and source-code
```javascript
precompile = function (input, options) {
  return _handlebarsCompilerCompiler.precompile(input, options, hb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.print"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>print (ast)](#apidoc.element.gulp-compile-handlebars.Handlebars.print)
- description and source-code
```javascript
function print(ast) {
  return new PrintVisitor().accept(ast);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.template"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>template (spec)](#apidoc.element.gulp-compile-handlebars.Handlebars.template)
- description and source-code
```javascript
template = function (spec) {
  return runtime.template(spec, hb);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-compile-handlebars.Handlebars.Compiler"></a>[module gulp-compile-handlebars.Handlebars.Compiler](#apidoc.module.gulp-compile-handlebars.Handlebars.Compiler)

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.Compiler"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>Compiler ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.Compiler)
- description and source-code
```javascript
function Compiler() {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-compile-handlebars.Handlebars.Compiler.prototype"></a>[module gulp-compile-handlebars.Handlebars.Compiler.prototype](#apidoc.module.gulp-compile-handlebars.Handlebars.Compiler.prototype)

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.BlockStatement"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>BlockStatement (block)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.BlockStatement)
- description and source-code
```javascript
function BlockStatement(block) {
  transformLiteralToPath(block);

  var program = block.program,
      inverse = block.inverse;

  program = program && this.compileProgram(program);
  inverse = inverse && this.compileProgram(inverse);

  var type = this.classifySexpr(block);

  if (type === 'helper') {
    this.helperSexpr(block, program, inverse);
  } else if (type === 'simple') {
    this.simpleSexpr(block);

    // now that the simple mustache is resolved, we need to
    // evaluate it by executing 'blockHelperMissing'
    this.opcode('pushProgram', program);
    this.opcode('pushProgram', inverse);
    this.opcode('emptyHash');
    this.opcode('blockValue', block.path.original);
  } else {
    this.ambiguousSexpr(block, program, inverse);

    // now that the simple mustache is resolved, we need to
    // evaluate it by executing 'blockHelperMissing'
    this.opcode('pushProgram', program);
    this.opcode('pushProgram', inverse);
    this.opcode('emptyHash');
    this.opcode('ambiguousBlockValue');
  }

  this.opcode('append');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.BooleanLiteral"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>BooleanLiteral (bool)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.BooleanLiteral)
- description and source-code
```javascript
function BooleanLiteral(bool) {
  this.opcode('pushLiteral', bool.value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.CommentStatement"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>CommentStatement ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.CommentStatement)
- description and source-code
```javascript
function CommentStatement() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.ContentStatement"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>ContentStatement (content)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.ContentStatement)
- description and source-code
```javascript
function ContentStatement(content) {
  if (content.value) {
    this.opcode('appendContent', content.value);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.Decorator"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>Decorator (decorator)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.Decorator)
- description and source-code
```javascript
function Decorator(decorator) {
  this.DecoratorBlock(decorator);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.DecoratorBlock"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>DecoratorBlock (decorator)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.DecoratorBlock)
- description and source-code
```javascript
function DecoratorBlock(decorator) {
  var program = decorator.program && this.compileProgram(decorator.program);
  var params = this.setupFullMustacheParams(decorator, program, undefined),
      path = decorator.path;

  this.useDecorators = true;
  this.opcode('registerDecorator', params.length, path.original);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.Hash"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>Hash (hash)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.Hash)
- description and source-code
```javascript
function Hash(hash) {
  var pairs = hash.pairs,
      i = 0,
      l = pairs.length;

  this.opcode('pushHash');

  for (; i < l; i++) {
    this.pushParam(pairs[i].value);
  }
  while (i--) {
    this.opcode('assignToHash', pairs[i].key);
  }
  this.opcode('popHash');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.MustacheStatement"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>MustacheStatement (mustache)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.MustacheStatement)
- description and source-code
```javascript
function MustacheStatement(mustache) {
  this.SubExpression(mustache);

  if (mustache.escaped && !this.options.noEscape) {
    this.opcode('appendEscaped');
  } else {
    this.opcode('append');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.NullLiteral"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>NullLiteral ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.NullLiteral)
- description and source-code
```javascript
function NullLiteral() {
  this.opcode('pushLiteral', 'null');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.NumberLiteral"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>NumberLiteral (number)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.NumberLiteral)
- description and source-code
```javascript
function NumberLiteral(number) {
  this.opcode('pushLiteral', number.value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.PartialBlockStatement"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>PartialBlockStatement (partialBlock)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.PartialBlockStatement)
- description and source-code
```javascript
function PartialBlockStatement(partialBlock) {
  this.PartialStatement(partialBlock);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.PartialStatement"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>PartialStatement (partial)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.PartialStatement)
- description and source-code
```javascript
function PartialStatement(partial) {
  this.usePartial = true;

  var program = partial.program;
  if (program) {
    program = this.compileProgram(partial.program);
  }

  var params = partial.params;
  if (params.length > 1) {
    throw new _exception2['default']('Unsupported number of partial arguments: ' + params.length, partial);
  } else if (!params.length) {
    if (this.options.explicitPartialContext) {
      this.opcode('pushLiteral', 'undefined');
    } else {
      params.push({ type: 'PathExpression', parts: [], depth: 0 });
    }
  }

  var partialName = partial.name.original,
      isDynamic = partial.name.type === 'SubExpression';
  if (isDynamic) {
    this.accept(partial.name);
  }

  this.setupFullMustacheParams(partial, program, undefined, true);

  var indent = partial.indent || '';
  if (this.options.preventIndent && indent) {
    this.opcode('appendContent', indent);
    indent = '';
  }

  this.opcode('invokePartial', isDynamic, partialName, indent);
  this.opcode('append');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.PathExpression"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>PathExpression (path)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.PathExpression)
- description and source-code
```javascript
function PathExpression(path) {
  this.addDepth(path.depth);
  this.opcode('getContext', path.depth);

  var name = path.parts[0],
      scoped = _ast2['default'].helpers.scopedId(path),
      blockParamId = !path.depth && !scoped && this.blockParamIndex(name);

  if (blockParamId) {
    this.opcode('lookupBlockParam', blockParamId, path.parts);
  } else if (!name) {
    // Context reference, i.e. '{{foo .}}' or '{{foo ..}}'
    this.opcode('pushContext');
  } else if (path.data) {
    this.options.data = true;
    this.opcode('lookupData', path.depth, path.parts, path.strict);
  } else {
    this.opcode('lookupOnContext', path.parts, path.falsy, path.strict, scoped);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.Program"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>Program (program)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.Program)
- description and source-code
```javascript
function Program(program) {
  this.options.blockParams.unshift(program.blockParams);

  var body = program.body,
      bodyLength = body.length;
  for (var i = 0; i < bodyLength; i++) {
    this.accept(body[i]);
  }

  this.options.blockParams.shift();

  this.isSimple = bodyLength === 1;
  this.blockParams = program.blockParams ? program.blockParams.length : 0;

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.StringLiteral"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>StringLiteral (string)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.StringLiteral)
- description and source-code
```javascript
function StringLiteral(string) {
  this.opcode('pushString', string.value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.SubExpression"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>SubExpression (sexpr)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.SubExpression)
- description and source-code
```javascript
function SubExpression(sexpr) {
  transformLiteralToPath(sexpr);
  var type = this.classifySexpr(sexpr);

  if (type === 'simple') {
    this.simpleSexpr(sexpr);
  } else if (type === 'helper') {
    this.helperSexpr(sexpr);
  } else {
    this.ambiguousSexpr(sexpr);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.UndefinedLiteral"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>UndefinedLiteral ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.UndefinedLiteral)
- description and source-code
```javascript
function UndefinedLiteral() {
  this.opcode('pushLiteral', 'undefined');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.accept"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>accept (node)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.accept)
- description and source-code
```javascript
function accept(node) {
<span class="apidocCodeCommentSpan">  /* istanbul ignore next: Sanity code */
</span>  if (!this[node.type]) {
    throw new _exception2['default']('Unknown type: ' + node.type, node);
  }

  this.sourceNode.unshift(node);
  var ret = this[node.type](node);
  this.sourceNode.shift();
  return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.addDepth"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>addDepth (depth)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.addDepth)
- description and source-code
```javascript
function addDepth(depth) {
  if (!depth) {
    return;
  }

  this.useDepths = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.ambiguousSexpr"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>ambiguousSexpr (sexpr, program, inverse)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.ambiguousSexpr)
- description and source-code
```javascript
function ambiguousSexpr(sexpr, program, inverse) {
  var path = sexpr.path,
      name = path.parts[0],
      isBlock = program != null || inverse != null;

  this.opcode('getContext', path.depth);

  this.opcode('pushProgram', program);
  this.opcode('pushProgram', inverse);

  path.strict = true;
  this.accept(path);

  this.opcode('invokeAmbiguous', name, isBlock);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.blockParamIndex"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>blockParamIndex (name)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.blockParamIndex)
- description and source-code
```javascript
function blockParamIndex(name) {
  for (var depth = 0, len = this.options.blockParams.length; depth < len; depth++) {
    var blockParams = this.options.blockParams[depth],
        param = blockParams && _utils.indexOf(blockParams, name);
    if (blockParams && param >= 0) {
      return [depth, param];
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.classifySexpr"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>classifySexpr (sexpr)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.classifySexpr)
- description and source-code
```javascript
function classifySexpr(sexpr) {
  var isSimple = _ast2['default'].helpers.simpleId(sexpr.path);

  var isBlockParam = isSimple && !!this.blockParamIndex(sexpr.path.parts[0]);

  // a mustache is an eligible helper if:
  // * its id is simple (a single part, not 'this' or '..')
  var isHelper = !isBlockParam && _ast2['default'].helpers.helperExpression(sexpr);

  // if a mustache is an eligible helper but not a definite
  // helper, it is ambiguous, and will be resolved in a later
  // pass or at runtime.
  var isEligible = !isBlockParam && (isHelper || isSimple);

  // if ambiguous, we can possibly resolve the ambiguity now
  // An eligible helper is one that does not have a complex path, i.e. 'this.foo', '../foo' etc.
  if (isEligible && !isHelper) {
    var _name2 = sexpr.path.parts[0],
        options = this.options;

    if (options.knownHelpers[_name2]) {
      isHelper = true;
    } else if (options.knownHelpersOnly) {
      isEligible = false;
    }
  }

  if (isHelper) {
    return 'helper';
  } else if (isEligible) {
    return 'ambiguous';
  } else {
    return 'simple';
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.compile"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>compile (program, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.compile)
- description and source-code
```javascript
function compile(program, options) {
  this.sourceNode = [];
  this.opcodes = [];
  this.children = [];
  this.options = options;
  this.stringParams = options.stringParams;
  this.trackIds = options.trackIds;

  options.blockParams = options.blockParams || [];

  // These changes will propagate to the other compiler components
  var knownHelpers = options.knownHelpers;
  options.knownHelpers = {
    'helperMissing': true,
    'blockHelperMissing': true,
    'each': true,
    'if': true,
    'unless': true,
    'with': true,
    'log': true,
    'lookup': true
  };
  if (knownHelpers) {
    for (var _name in knownHelpers) {
<span class="apidocCodeCommentSpan">      /* istanbul ignore else */
</span>      if (_name in knownHelpers) {
        options.knownHelpers[_name] = knownHelpers[_name];
      }
    }
  }

  return this.accept(program);
}
```
- example usage
```shell
...
				mockPartials(fileContents);
			}

			// Enable gulp-data usage, Extend default data with data from file.data
			if(file.data){
				_data = extend(_data, file.data);
			}
			var template = Handlebars.compile(fileContents, options.compile);
			file.contents = new Buffer(template(_data));
		} catch (err) {
			this.emit('error', new gutil.PluginError('gulp-compile-handlebars', err));
		}

		this.push(file);
		cb();
...
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.compileProgram"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>compileProgram (program)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.compileProgram)
- description and source-code
```javascript
function compileProgram(program) {
  var childCompiler = new this.compiler(),
      // eslint-disable-line new-cap
  result = childCompiler.compile(program, this.options),
      guid = this.guid++;

  this.usePartial = this.usePartial || result.usePartial;

  this.children[guid] = result;
  this.useDepths = this.useDepths || result.useDepths;

  return guid;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.compiler"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>compiler ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.compiler)
- description and source-code
```javascript
function Compiler() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.equals"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>equals (other)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.equals)
- description and source-code
```javascript
function equals(other) {
  var len = this.opcodes.length;
  if (other.opcodes.length !== len) {
    return false;
  }

  for (var i = 0; i < len; i++) {
    var opcode = this.opcodes[i],
        otherOpcode = other.opcodes[i];
    if (opcode.opcode !== otherOpcode.opcode || !argEquals(opcode.args, otherOpcode.args)) {
      return false;
    }
  }

  // We know that length is the same between the two arrays because they are directly tied
  // to the opcode behavior above.
  len = this.children.length;
  for (var i = 0; i < len; i++) {
    if (!this.children[i].equals(other.children[i])) {
      return false;
    }
  }

  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.helperSexpr"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>helperSexpr (sexpr, program, inverse)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.helperSexpr)
- description and source-code
```javascript
function helperSexpr(sexpr, program, inverse) {
  var params = this.setupFullMustacheParams(sexpr, program, inverse),
      path = sexpr.path,
      name = path.parts[0];

  if (this.options.knownHelpers[name]) {
    this.opcode('invokeKnownHelper', params.length, name);
  } else if (this.options.knownHelpersOnly) {
    throw new _exception2['default']('You specified knownHelpersOnly, but used the unknown helper ' + name, sexpr);
  } else {
    path.strict = true;
    path.falsy = true;

    this.accept(path);
    this.opcode('invokeHelper', params.length, path.original, _ast2['default'].helpers.simpleId(path));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.opcode"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>opcode (name)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.opcode)
- description and source-code
```javascript
function opcode(name) {
  this.opcodes.push({ opcode: name, args: slice.call(arguments, 1), loc: this.sourceNode[0].loc });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.pushParam"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>pushParam (val)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.pushParam)
- description and source-code
```javascript
function pushParam(val) {
  var value = val.value != null ? val.value : val.original || '';

  if (this.stringParams) {
    if (value.replace) {
      value = value.replace(/^(\.?\.\/)*/g, '').replace(/\//g, '.');
    }

    if (val.depth) {
      this.addDepth(val.depth);
    }
    this.opcode('getContext', val.depth || 0);
    this.opcode('pushStringParam', value, val.type);

    if (val.type === 'SubExpression') {
      // SubExpressions get evaluated and passed in
      // in string params mode.
      this.accept(val);
    }
  } else {
    if (this.trackIds) {
      var blockParamIndex = undefined;
      if (val.parts && !_ast2['default'].helpers.scopedId(val) && !val.depth) {
        blockParamIndex = this.blockParamIndex(val.parts[0]);
      }
      if (blockParamIndex) {
        var blockParamChild = val.parts.slice(1).join('.');
        this.opcode('pushId', 'BlockParam', blockParamIndex, blockParamChild);
      } else {
        value = val.original || value;
        if (value.replace) {
          value = value.replace(/^this(?:\.|$)/, '').replace(/^\.\//, '').replace(/^\.$/, '');
        }

        this.opcode('pushId', val.type, value);
      }
    }
    this.accept(val);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.pushParams"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>pushParams (params)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.pushParams)
- description and source-code
```javascript
function pushParams(params) {
  for (var i = 0, l = params.length; i < l; i++) {
    this.pushParam(params[i]);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.setupFullMustacheParams"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>setupFullMustacheParams (sexpr, program, inverse, omitEmpty)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.setupFullMustacheParams)
- description and source-code
```javascript
function setupFullMustacheParams(sexpr, program, inverse, omitEmpty) {
  var params = sexpr.params;
  this.pushParams(params);

  this.opcode('pushProgram', program);
  this.opcode('pushProgram', inverse);

  if (sexpr.hash) {
    this.accept(sexpr.hash);
  } else {
    this.opcode('emptyHash', omitEmpty);
  }

  return params;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.simpleSexpr"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Compiler.prototype.</span>simpleSexpr (sexpr)](#apidoc.element.gulp-compile-handlebars.Handlebars.Compiler.prototype.simpleSexpr)
- description and source-code
```javascript
function simpleSexpr(sexpr) {
  var path = sexpr.path;
  path.strict = true;
  this.accept(path);
  this.opcode('resolvePossibleLambda');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment"></a>[module gulp-compile-handlebars.Handlebars.HandlebarsEnvironment](#apidoc.module.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment)

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.HandlebarsEnvironment"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>HandlebarsEnvironment (helpers, partials, decorators)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.HandlebarsEnvironment)
- description and source-code
```javascript
function HandlebarsEnvironment(helpers, partials, decorators) {
  this.helpers = helpers || {};
  this.partials = partials || {};
  this.decorators = decorators || {};

  _helpers.registerDefaultHelpers(this);
  _decorators.registerDefaultDecorators(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype"></a>[module gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype](#apidoc.module.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype)

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.</span>constructor (helpers, partials, decorators)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.constructor)
- description and source-code
```javascript
function HandlebarsEnvironment(helpers, partials, decorators) {
  this.helpers = helpers || {};
  this.partials = partials || {};
  this.decorators = decorators || {};

  _helpers.registerDefaultHelpers(this);
  _decorators.registerDefaultDecorators(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.log"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.</span>log (level)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.log)
- description and source-code
```javascript
function log(level) {
  level = logger.lookupLevel(level);

  if (typeof console !== 'undefined' && logger.lookupLevel(logger.level) <= level) {
    var method = logger.methodMap[level];
    if (!console[method]) {
      // eslint-disable-line no-console
      method = 'log';
    }

    for (var _len = arguments.length, message = Array(_len > 1 ? _len - 1 : 0), _key = 1; _key < _len; _key++) {
      message[_key - 1] = arguments[_key];
    }

    console[method].apply(console, message); // eslint-disable-line no-console
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.registerDecorator"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.</span>registerDecorator (name, fn)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.registerDecorator)
- description and source-code
```javascript
function registerDecorator(name, fn) {
  if (_utils.toString.call(name) === objectType) {
    if (fn) {
      throw new _exception2['default']('Arg not supported with multiple decorators');
    }
    _utils.extend(this.decorators, name);
  } else {
    this.decorators[name] = fn;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.registerHelper"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.</span>registerHelper (name, fn)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.registerHelper)
- description and source-code
```javascript
function registerHelper(name, fn) {
  if (_utils.toString.call(name) === objectType) {
    if (fn) {
      throw new _exception2['default']('Arg not supported with multiple helpers');
    }
    _utils.extend(this.helpers, name);
  } else {
    this.helpers[name] = fn;
  }
}
```
- example usage
```shell
...
		for(var p in options.partials){
			Handlebars.registerPartial(p, options.partials[p]);
		}
	}
	//Go through a helpers object
	if(options.helpers){
		for(var h in options.helpers){
			Handlebars.registerHelper(h, options.helpers[h]);
		}
	}

	// Do not search for more than 10 nestings
	var maxDepth = 10;
	// Process only files with given extension names
	var allowedExtensions = ['hb', 'hbs', 'handlebars', 'html'];
...
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.registerPartial"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.</span>registerPartial (name, partial)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.registerPartial)
- description and source-code
```javascript
function registerPartial(name, partial) {
  if (_utils.toString.call(name) === objectType) {
    _utils.extend(this.partials, name);
  } else {
    if (typeof partial === 'undefined') {
      throw new _exception2['default']('Attempting to register a partial called "' + name + '" as undefined');
    }
    this.partials[name] = partial;
  }
}
```
- example usage
```shell
...
function handlebars(data, opts) {

	var options = opts || {};
	
	//Go through a partials object
	if(options.partials){
		for(var p in options.partials){
			Handlebars.registerPartial(p, options.partials[p]);
		}
	}
	//Go through a helpers object
	if(options.helpers){
		for(var h in options.helpers){
			Handlebars.registerHelper(h, options.helpers[h]);
		}
...
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.unregisterDecorator"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.</span>unregisterDecorator (name)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.unregisterDecorator)
- description and source-code
```javascript
function unregisterDecorator(name) {
  delete this.decorators[name];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.unregisterHelper"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.</span>unregisterHelper (name)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.unregisterHelper)
- description and source-code
```javascript
function unregisterHelper(name) {
  delete this.helpers[name];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.unregisterPartial"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.</span>unregisterPartial (name)](#apidoc.element.gulp-compile-handlebars.Handlebars.HandlebarsEnvironment.prototype.unregisterPartial)
- description and source-code
```javascript
function unregisterPartial(name) {
  delete this.partials[name];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-compile-handlebars.Handlebars.JavaScriptCompiler"></a>[module gulp-compile-handlebars.Handlebars.JavaScriptCompiler](#apidoc.module.gulp-compile-handlebars.Handlebars.JavaScriptCompiler)

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.JavaScriptCompiler"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>JavaScriptCompiler ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.JavaScriptCompiler)
- description and source-code
```javascript
function JavaScriptCompiler() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.isValidJavaScriptVariableName"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.</span>isValidJavaScriptVariableName (name)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.isValidJavaScriptVariableName)
- description and source-code
```javascript
isValidJavaScriptVariableName = function (name) {
  return !JavaScriptCompiler.RESERVED_WORDS[name] && /^[a-zA-Z_$][0-9a-zA-Z_$]*$/.test(name);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype"></a>[module gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype](#apidoc.module.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype)

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.aliasable"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>aliasable (name)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.aliasable)
- description and source-code
```javascript
function aliasable(name) {
  var ret = this.aliases[name];
  if (ret) {
    ret.referenceCount++;
    return ret;
  }

  ret = this.aliases[name] = this.source.wrap(name);
  ret.aliasable = true;
  ret.referenceCount = 1;

  return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.ambiguousBlockValue"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>ambiguousBlockValue ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.ambiguousBlockValue)
- description and source-code
```javascript
function ambiguousBlockValue() {
  // We're being a bit cheeky and reusing the options value from the prior exec
  var blockHelperMissing = this.aliasable('helpers.blockHelperMissing'),
      params = [this.contextName(0)];
  this.setupHelperArgs('', 0, params, true);

  this.flushInline();

  var current = this.topStack();
  params.splice(1, 0, current);

  this.pushSource(['if (!', this.lastHelper, ') { ', current, ' = ', this.source.functionCall(blockHelperMissing, 'call', params
), '}']);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.append"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>append ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.append)
- description and source-code
```javascript
function append() {
  if (this.isInline()) {
    this.replaceStack(function (current) {
      return [' != null ? ', current, ' : ""'];
    });

    this.pushSource(this.appendToBuffer(this.popStack()));
  } else {
    var local = this.popStack();
    this.pushSource(['if (', local, ' != null) { ', this.appendToBuffer(local, undefined, true), ' }']);
    if (this.environment.isSimple) {
      this.pushSource(['else { ', this.appendToBuffer("''", undefined, true), ' }']);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.appendContent"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>appendContent (content)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.appendContent)
- description and source-code
```javascript
function appendContent(content) {
  if (this.pendingContent) {
    content = this.pendingContent + content;
  } else {
    this.pendingLocation = this.source.currentLocation;
  }

  this.pendingContent = content;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.appendEscaped"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>appendEscaped ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.appendEscaped)
- description and source-code
```javascript
function appendEscaped() {
  this.pushSource(this.appendToBuffer([this.aliasable('container.escapeExpression'), '(', this.popStack(), ')']));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.appendToBuffer"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>appendToBuffer (source, location, explicit)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.appendToBuffer)
- description and source-code
```javascript
function appendToBuffer(source, location, explicit) {
  // Force a source as this simplifies the merge logic.
  if (!_utils.isArray(source)) {
    source = [source];
  }
  source = this.source.wrap(source, location);

  if (this.environment.isSimple) {
    return ['return ', source, ';'];
  } else if (explicit) {
    // This is a case where the buffer operation occurs as a child of another
    // construct, generally braces. We have to explicitly output these buffer
    // operations to ensure that the emitted code goes in the correct location.
    return ['buffer += ', source, ';'];
  } else {
    source.appendToBuffer = true;
    return source;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.assignToHash"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>assignToHash (key)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.assignToHash)
- description and source-code
```javascript
function assignToHash(key) {
  var value = this.popStack(),
      context = undefined,
      type = undefined,
      id = undefined;

  if (this.trackIds) {
    id = this.popStack();
  }
  if (this.stringParams) {
    type = this.popStack();
    context = this.popStack();
  }

  var hash = this.hash;
  if (context) {
    hash.contexts[key] = context;
  }
  if (type) {
    hash.types[key] = type;
  }
  if (id) {
    hash.ids[key] = id;
  }
  hash.values[key] = value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.blockValue"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>blockValue (name)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.blockValue)
- description and source-code
```javascript
function blockValue(name) {
  var blockHelperMissing = this.aliasable('helpers.blockHelperMissing'),
      params = [this.contextName(0)];
  this.setupHelperArgs(name, 0, params);

  var blockName = this.popStack();
  params.splice(1, 0, blockName);

  this.push(this.source.functionCall(blockHelperMissing, 'call', params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.compile"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>compile (environment, options, context, asObject)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.compile)
- description and source-code
```javascript
function compile(environment, options, context, asObject) {
  this.environment = environment;
  this.options = options;
  this.stringParams = this.options.stringParams;
  this.trackIds = this.options.trackIds;
  this.precompile = !asObject;

  this.name = this.environment.name;
  this.isChild = !!context;
  this.context = context || {
    decorators: [],
    programs: [],
    environments: []
  };

  this.preamble();

  this.stackSlot = 0;
  this.stackVars = [];
  this.aliases = {};
  this.registers = { list: [] };
  this.hashes = [];
  this.compileStack = [];
  this.inlineStack = [];
  this.blockParams = [];

  this.compileChildren(environment, options);

  this.useDepths = this.useDepths || environment.useDepths || environment.useDecorators || this.options.compat;
  this.useBlockParams = this.useBlockParams || environment.useBlockParams;

  var opcodes = environment.opcodes,
      opcode = undefined,
      firstLoc = undefined,
      i = undefined,
      l = undefined;

  for (i = 0, l = opcodes.length; i < l; i++) {
    opcode = opcodes[i];

    this.source.currentLocation = opcode.loc;
    firstLoc = firstLoc || opcode.loc;
    this[opcode.opcode].apply(this, opcode.args);
  }

  // Flush any trailing content that might be pending.
  this.source.currentLocation = firstLoc;
  this.pushSource('');

<span class="apidocCodeCommentSpan">  /* istanbul ignore next */
</span>  if (this.stackSlot || this.inlineStack.length || this.compileStack.length) {
    throw new _exception2['default']('Compile completed with content left on stack');
  }

  if (!this.decorators.isEmpty()) {
    this.useDecorators = true;

    this.decorators.prepend('var decorators = container.decorators;\n');
    this.decorators.push('return fn;');

    if (asObject) {
      this.decorators = Function.apply(this, ['fn', 'props', 'container', 'depth0', 'data', 'blockParams', 'depths', this.decorators
.merge()]);
    } else {
      this.decorators.prepend('function(fn, props, container, depth0, data, blockParams, depths) {\n');
      this.decorators.push('}\n');
      this.decorators = this.decorators.merge();
    }
  } else {
    this.decorators = undefined;
  }

  var fn = this.createFunctionContext(asObject);
  if (!this.isChild) {
    var ret = {
      compiler: this.compilerInfo(),
      main: fn
    };

    if (this.decorators) {
      ret.main_d = this.decorators; // eslint-disable-line camelcase
      ret.useDecorators = true;
    }

    var _context = this.context;
    var programs = _context.programs;
    var decorators = _context.decorators;

    for (i = 0, l = programs.length; i < l; i++) {
      if (programs[i]) {
        ret[i] = programs[i];
        if (decorators[i]) {
          ret[i + '_d'] = decorators[i];
          ret.useDecorators = true;
        }
      }
    }

    if (this.environment.usePartial) {
      ret.usePartial = true;
    }
    if (this.options.data) {
      ret.useData = true;
    }
    if (this.useDepths) {
      ret.useDepths = true;
    }
    if (this.useBlockParams) {
      ret.useBlockParams = true;
    }
    if (this.options.compat) {
      ret.compat = true;
    }

    if (!asObject) {
      ret.compiler = JSON.stringify(ret.compiler);

      this.source.currentLocation = { start: { line: 1, column: 0 } };
      ret = this.objectLiteral(ret);

      if (options.srcName) {
        ret = ret.toStringWithSourceMap({ file: options.destName });
        ret.map = ret.map && ret.map.toString();
      } else {
        ret = ret.toString();
      }
    } else {
      ret.compilerOptions = this.options;
    }

    return ret;
  } else {
    return fn;
  }
}
```
- example usage
```shell
...
				mockPartials(fileContents);
			}

			// Enable gulp-data usage, Extend default data with data from file.data
			if(file.data){
				_data = extend(_data, file.data);
			}
			var template = Handlebars.compile(fileContents, options.compile);
			file.contents = new Buffer(template(_data));
		} catch (err) {
			this.emit('error', new gutil.PluginError('gulp-compile-handlebars', err));
		}

		this.push(file);
		cb();
...
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.compileChildren"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>compileChildren (environment, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.compileChildren)
- description and source-code
```javascript
function compileChildren(environment, options) {
  var children = environment.children,
      child = undefined,
      compiler = undefined;

  for (var i = 0, l = children.length; i < l; i++) {
    child = children[i];
    compiler = new this.compiler(); // eslint-disable-line new-cap

    var existing = this.matchExistingProgram(child);

    if (existing == null) {
      this.context.programs.push(''); // Placeholder to prevent name conflicts for nested children
      var index = this.context.programs.length;
      child.index = index;
      child.name = 'program' + index;
      this.context.programs[index] = compiler.compile(child, options, this.context, !this.precompile);
      this.context.decorators[index] = compiler.decorators;
      this.context.environments[index] = child;

      this.useDepths = this.useDepths || compiler.useDepths;
      this.useBlockParams = this.useBlockParams || compiler.useBlockParams;
      child.useDepths = this.useDepths;
      child.useBlockParams = this.useBlockParams;
    } else {
      child.index = existing.index;
      child.name = 'program' + existing.index;

      this.useDepths = this.useDepths || existing.useDepths;
      this.useBlockParams = this.useBlockParams || existing.useBlockParams;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.compiler"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>compiler ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.compiler)
- description and source-code
```javascript
function JavaScriptCompiler() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.compilerInfo"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>compilerInfo ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.compilerInfo)
- description and source-code
```javascript
function compilerInfo() {
  var revision = _base.COMPILER_REVISION,
      versions = _base.REVISION_CHANGES[revision];
  return [revision, versions];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.contextName"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>contextName (context)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.contextName)
- description and source-code
```javascript
function contextName(context) {
  if (this.useDepths && context) {
    return 'depths[' + context + ']';
  } else {
    return 'depth' + context;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.createFunctionContext"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>createFunctionContext (asObject)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.createFunctionContext)
- description and source-code
```javascript
function createFunctionContext(asObject) {
  var varDeclarations = '';

  var locals = this.stackVars.concat(this.registers.list);
  if (locals.length > 0) {
    varDeclarations += ', ' + locals.join(', ');
  }

  // Generate minimizer alias mappings
  //
  // When using true SourceNodes, this will update all references to the given alias
  // as the source nodes are reused in situ. For the non-source node compilation mode,
  // aliases will not be used, but this case is already being run on the client and
  // we aren't concern about minimizing the template size.
  var aliasCount = 0;
  for (var alias in this.aliases) {
    // eslint-disable-line guard-for-in
    var node = this.aliases[alias];

    if (this.aliases.hasOwnProperty(alias) && node.children && node.referenceCount > 1) {
      varDeclarations += ', alias' + ++aliasCount + '=' + alias;
      node.children[0] = 'alias' + aliasCount;
    }
  }

  var params = ['container', 'depth0', 'helpers', 'partials', 'data'];

  if (this.useBlockParams || this.useDepths) {
    params.push('blockParams');
  }
  if (this.useDepths) {
    params.push('depths');
  }

  // Perform a second pass over the output to merge content when possible
  var source = this.mergeSource(varDeclarations);

  if (asObject) {
    params.push(source);

    return Function.apply(this, params);
  } else {
    return this.source.wrap(['function(', params.join(','), ') {\n  ', source, '}']);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.depthedLookup"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>depthedLookup (name)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.depthedLookup)
- description and source-code
```javascript
function depthedLookup(name) {
  return [this.aliasable('container.lookup'), '(depths, "', name, '")'];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.emptyHash"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>emptyHash (omitEmpty)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.emptyHash)
- description and source-code
```javascript
function emptyHash(omitEmpty) {
  if (this.trackIds) {
    this.push('{}'); // hashIds
  }
  if (this.stringParams) {
    this.push('{}'); // hashContexts
    this.push('{}'); // hashTypes
  }
  this.pushStackLiteral(omitEmpty ? 'undefined' : '{}');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.flushInline"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>flushInline ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.flushInline)
- description and source-code
```javascript
function flushInline() {
  var inlineStack = this.inlineStack;
  this.inlineStack = [];
  for (var i = 0, len = inlineStack.length; i < len; i++) {
    var entry = inlineStack[i];
<span class="apidocCodeCommentSpan">    /* istanbul ignore if */
</span>    if (entry instanceof Literal) {
      this.compileStack.push(entry);
    } else {
      var stack = this.incrStack();
      this.pushSource([stack, ' = ', entry, ';']);
      this.compileStack.push(stack);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.getContext"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>getContext (depth)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.getContext)
- description and source-code
```javascript
function getContext(depth) {
  this.lastContext = depth;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.incrStack"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>incrStack ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.incrStack)
- description and source-code
```javascript
function incrStack() {
  this.stackSlot++;
  if (this.stackSlot > this.stackVars.length) {
    this.stackVars.push('stack' + this.stackSlot);
  }
  return this.topStackName();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.initializeBuffer"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>initializeBuffer ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.initializeBuffer)
- description and source-code
```javascript
function initializeBuffer() {
  return this.quotedString('');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.invokeAmbiguous"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>invokeAmbiguous (name, helperCall)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.invokeAmbiguous)
- description and source-code
```javascript
function invokeAmbiguous(name, helperCall) {
  this.useRegister('helper');

  var nonHelper = this.popStack();

  this.emptyHash();
  var helper = this.setupHelper(0, name, helperCall);

  var helperName = this.lastHelper = this.nameLookup('helpers', name, 'helper');

  var lookup = ['(', '(helper = ', helperName, ' || ', nonHelper, ')'];
  if (!this.options.strict) {
    lookup[0] = '(helper = ';
    lookup.push(' != null ? helper : ', this.aliasable('helpers.helperMissing'));
  }

  this.push(['(', lookup, helper.paramsInit ? ['),(', helper.paramsInit] : [], '),', '(typeof helper === ', this.aliasable('"function
"'), ' ? ', this.source.functionCall('helper', 'call', helper.callParams), ' : helper))']);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.invokeHelper"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>invokeHelper (paramSize, name, isSimple)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.invokeHelper)
- description and source-code
```javascript
function invokeHelper(paramSize, name, isSimple) {
  var nonHelper = this.popStack(),
      helper = this.setupHelper(paramSize, name),
      simple = isSimple ? [helper.name, ' || '] : '';

  var lookup = ['('].concat(simple, nonHelper);
  if (!this.options.strict) {
    lookup.push(' || ', this.aliasable('helpers.helperMissing'));
  }
  lookup.push(')');

  this.push(this.source.functionCall(lookup, 'call', helper.callParams));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.invokeKnownHelper"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>invokeKnownHelper (paramSize, name)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.invokeKnownHelper)
- description and source-code
```javascript
function invokeKnownHelper(paramSize, name) {
  var helper = this.setupHelper(paramSize, name);
  this.push(this.source.functionCall(helper.name, 'call', helper.callParams));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.invokePartial"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>invokePartial (isDynamic, name, indent)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.invokePartial)
- description and source-code
```javascript
function invokePartial(isDynamic, name, indent) {
  var params = [],
      options = this.setupParams(name, 1, params);

  if (isDynamic) {
    name = this.popStack();
    delete options.name;
  }

  if (indent) {
    options.indent = JSON.stringify(indent);
  }
  options.helpers = 'helpers';
  options.partials = 'partials';
  options.decorators = 'container.decorators';

  if (!isDynamic) {
    params.unshift(this.nameLookup('partials', name, 'partial'));
  } else {
    params.unshift(name);
  }

  if (this.options.compat) {
    options.depths = 'depths';
  }
  options = this.objectLiteral(options);
  params.push(options);

  this.push(this.source.functionCall('container.invokePartial', '', params));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.isInline"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>isInline ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.isInline)
- description and source-code
```javascript
function isInline() {
  return this.inlineStack.length;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.lookupBlockParam"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>lookupBlockParam (blockParamId, parts)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.lookupBlockParam)
- description and source-code
```javascript
function lookupBlockParam(blockParamId, parts) {
  this.useBlockParams = true;

  this.push(['blockParams[', blockParamId[0], '][', blockParamId[1], ']']);
  this.resolvePath('context', parts, 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.lookupData"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>lookupData (depth, parts, strict)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.lookupData)
- description and source-code
```javascript
function lookupData(depth, parts, strict) {
  if (!depth) {
    this.pushStackLiteral('data');
  } else {
    this.pushStackLiteral('container.data(data, ' + depth + ')');
  }

  this.resolvePath('data', parts, 0, true, strict);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.lookupOnContext"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>lookupOnContext (parts, falsy, strict, scoped)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.lookupOnContext)
- description and source-code
```javascript
function lookupOnContext(parts, falsy, strict, scoped) {
  var i = 0;

  if (!scoped && this.options.compat && !this.lastContext) {
    // The depthed query is expected to handle the undefined logic for the root level that
    // is implemented below, so we evaluate that directly in compat mode
    this.push(this.depthedLookup(parts[i++]));
  } else {
    this.pushContext();
  }

  this.resolvePath('context', parts, i, falsy, strict);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.matchExistingProgram"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>matchExistingProgram (child)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.matchExistingProgram)
- description and source-code
```javascript
function matchExistingProgram(child) {
  for (var i = 0, len = this.context.environments.length; i < len; i++) {
    var environment = this.context.environments[i];
    if (environment && environment.equals(child)) {
      return environment;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.mergeSource"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>mergeSource (varDeclarations)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.mergeSource)
- description and source-code
```javascript
function mergeSource(varDeclarations) {
  var isSimple = this.environment.isSimple,
      appendOnly = !this.forceBuffer,
      appendFirst = undefined,
      sourceSeen = undefined,
      bufferStart = undefined,
      bufferEnd = undefined;
  this.source.each(function (line) {
    if (line.appendToBuffer) {
      if (bufferStart) {
        line.prepend('  + ');
      } else {
        bufferStart = line;
      }
      bufferEnd = line;
    } else {
      if (bufferStart) {
        if (!sourceSeen) {
          appendFirst = true;
        } else {
          bufferStart.prepend('buffer += ');
        }
        bufferEnd.add(';');
        bufferStart = bufferEnd = undefined;
      }

      sourceSeen = true;
      if (!isSimple) {
        appendOnly = false;
      }
    }
  });

  if (appendOnly) {
    if (bufferStart) {
      bufferStart.prepend('return ');
      bufferEnd.add(';');
    } else if (!sourceSeen) {
      this.source.push('return "";');
    }
  } else {
    varDeclarations += ', buffer = ' + (appendFirst ? '' : this.initializeBuffer());

    if (bufferStart) {
      bufferStart.prepend('return buffer + ');
      bufferEnd.add(';');
    } else {
      this.source.push('return buffer;');
    }
  }

  if (varDeclarations) {
    this.source.prepend('var ' + varDeclarations.substring(2) + (appendFirst ? '' : ';\n'));
  }

  return this.source.merge();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.nameLookup"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>nameLookup (parent, name)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.nameLookup)
- description and source-code
```javascript
function nameLookup(parent, name) {
  if (JavaScriptCompiler.isValidJavaScriptVariableName(name)) {
    return [parent, '.', name];
  } else {
    return [parent, '[', JSON.stringify(name), ']'];
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.objectLiteral"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>objectLiteral (obj)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.objectLiteral)
- description and source-code
```javascript
function objectLiteral(obj) {
  return this.source.objectLiteral(obj);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.popHash"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>popHash ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.popHash)
- description and source-code
```javascript
function popHash() {
  var hash = this.hash;
  this.hash = this.hashes.pop();

  if (this.trackIds) {
    this.push(this.objectLiteral(hash.ids));
  }
  if (this.stringParams) {
    this.push(this.objectLiteral(hash.contexts));
    this.push(this.objectLiteral(hash.types));
  }

  this.push(this.objectLiteral(hash.values));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.popStack"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>popStack (wrapped)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.popStack)
- description and source-code
```javascript
function popStack(wrapped) {
  var inline = this.isInline(),
      item = (inline ? this.inlineStack : this.compileStack).pop();

  if (!wrapped && item instanceof Literal) {
    return item.value;
  } else {
    if (!inline) {
<span class="apidocCodeCommentSpan">      /* istanbul ignore next */
</span>      if (!this.stackSlot) {
        throw new _exception2['default']('Invalid stack pop');
      }
      this.stackSlot--;
    }
    return item;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.preamble"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>preamble ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.preamble)
- description and source-code
```javascript
function preamble() {
  // track the last context pushed into place to allow skipping the
  // getContext opcode when it would be a noop
  this.lastContext = 0;
  this.source = new _codeGen2['default'](this.options.srcName);
  this.decorators = new _codeGen2['default'](this.options.srcName);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.programExpression"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>programExpression (guid)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.programExpression)
- description and source-code
```javascript
function programExpression(guid) {
  var child = this.environment.children[guid],
      programParams = [child.index, 'data', child.blockParams];

  if (this.useBlockParams || this.useDepths) {
    programParams.push('blockParams');
  }
  if (this.useDepths) {
    programParams.push('depths');
  }

  return 'container.program(' + programParams.join(', ') + ')';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.push"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>push (expr)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.push)
- description and source-code
```javascript
function push(expr) {
  if (!(expr instanceof Literal)) {
    expr = this.source.wrap(expr);
  }

  this.inlineStack.push(expr);
  return expr;
}
```
- example usage
```shell
...
	};


	return through.obj(function (file, enc, cb) {
		var _data = extend({}, data);

		if (file.isNull()) {
			this.push(file);
			return cb();
		}

		if (file.isStream()) {
			this.emit('error', new gutil.PluginError('gulp-compile-handlebars', 'Streaming not supported'));
			return cb();
		}
...
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushContext"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>pushContext ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushContext)
- description and source-code
```javascript
function pushContext() {
  this.pushStackLiteral(this.contextName(this.lastContext));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushHash"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>pushHash ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushHash)
- description and source-code
```javascript
function pushHash() {
  if (this.hash) {
    this.hashes.push(this.hash);
  }
  this.hash = { values: [], types: [], contexts: [], ids: [] };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushId"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>pushId (type, name, child)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushId)
- description and source-code
```javascript
function pushId(type, name, child) {
  if (type === 'BlockParam') {
    this.pushStackLiteral('blockParams[' + name[0] + '].path[' + name[1] + ']' + (child ? ' + ' + JSON.stringify('.' + child) : ''));
  } else if (type === 'PathExpression') {
    this.pushString(name);
  } else if (type === 'SubExpression') {
    this.pushStackLiteral('true');
  } else {
    this.pushStackLiteral('null');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushLiteral"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>pushLiteral (value)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushLiteral)
- description and source-code
```javascript
function pushLiteral(value) {
  this.pushStackLiteral(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushProgram"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>pushProgram (guid)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushProgram)
- description and source-code
```javascript
function pushProgram(guid) {
  if (guid != null) {
    this.pushStackLiteral(this.programExpression(guid));
  } else {
    this.pushStackLiteral(null);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushSource"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>pushSource (source)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushSource)
- description and source-code
```javascript
function pushSource(source) {
  if (this.pendingContent) {
    this.source.push(this.appendToBuffer(this.source.quotedString(this.pendingContent), this.pendingLocation));
    this.pendingContent = undefined;
  }

  if (source) {
    this.source.push(source);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushStackLiteral"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>pushStackLiteral (item)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushStackLiteral)
- description and source-code
```javascript
function pushStackLiteral(item) {
  this.push(new Literal(item));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushString"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>pushString (string)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushString)
- description and source-code
```javascript
function pushString(string) {
  this.pushStackLiteral(this.quotedString(string));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushStringParam"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>pushStringParam (string, type)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.pushStringParam)
- description and source-code
```javascript
function pushStringParam(string, type) {
  this.pushContext();
  this.pushString(type);

  // If it's a subexpression, the string result
  // will be pushed after this opcode.
  if (type !== 'SubExpression') {
    if (typeof string === 'string') {
      this.pushString(string);
    } else {
      this.pushStackLiteral(string);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.quotedString"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>quotedString (str)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.quotedString)
- description and source-code
```javascript
function quotedString(str) {
  return this.source.quotedString(str);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.registerDecorator"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>registerDecorator (paramSize, name)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.registerDecorator)
- description and source-code
```javascript
function registerDecorator(paramSize, name) {
  var foundDecorator = this.nameLookup('decorators', name, 'decorator'),
      options = this.setupHelperArgs(name, paramSize);

  this.decorators.push(['fn = ', this.decorators.functionCall(foundDecorator, '', ['fn', 'props', 'container', options]), ' || fn
;']);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.replaceStack"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>replaceStack (callback)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.replaceStack)
- description and source-code
```javascript
function replaceStack(callback) {
  var prefix = ['('],
      stack = undefined,
      createdStack = undefined,
      usedLiteral = undefined;

<span class="apidocCodeCommentSpan">  /* istanbul ignore next */
</span>  if (!this.isInline()) {
    throw new _exception2['default']('replaceStack on non-inline');
  }

  // We want to merge the inline statement into the replacement statement via ','
  var top = this.popStack(true);

  if (top instanceof Literal) {
    // Literals do not need to be inlined
    stack = [top.value];
    prefix = ['(', stack];
    usedLiteral = true;
  } else {
    // Get or create the current stack name for use by the inline
    createdStack = true;
    var _name = this.incrStack();

    prefix = ['((', this.push(_name), ' = ', top, ')'];
    stack = this.topStack();
  }

  var item = callback.call(this, stack);

  if (!usedLiteral) {
    this.popStack();
  }
  if (createdStack) {
    this.stackSlot--;
  }
  this.push(prefix.concat(item, ')'));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.resolvePath"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>resolvePath (type, parts, i, falsy, strict)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.resolvePath)
- description and source-code
```javascript
function resolvePath(type, parts, i, falsy, strict) {
  // istanbul ignore next

  var _this = this;

  if (this.options.strict || this.options.assumeObjects) {
    this.push(strictLookup(this.options.strict && strict, this, parts, type));
    return;
  }

  var len = parts.length;
  for (; i < len; i++) {
<span class="apidocCodeCommentSpan">    /* eslint-disable no-loop-func */
</span>    this.replaceStack(function (current) {
      var lookup = _this.nameLookup(current, parts[i], type);
      // We want to ensure that zero and false are handled properly if the context (falsy flag)
      // needs to have the special handling for these values.
      if (!falsy) {
        return [' != null ? ', lookup, ' : ', current];
      } else {
        // Otherwise we can use generic falsy handling
        return [' && ', lookup];
      }
    });
    /* eslint-enable no-loop-func */
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.resolvePossibleLambda"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>resolvePossibleLambda ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.resolvePossibleLambda)
- description and source-code
```javascript
function resolvePossibleLambda() {
  this.push([this.aliasable('container.lambda'), '(', this.popStack(), ', ', this.contextName(0), ')']);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.setupHelper"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>setupHelper (paramSize, name, blockHelper)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.setupHelper)
- description and source-code
```javascript
function setupHelper(paramSize, name, blockHelper) {
  var params = [],
      paramsInit = this.setupHelperArgs(name, paramSize, params, blockHelper);
  var foundHelper = this.nameLookup('helpers', name, 'helper'),
      callContext = this.aliasable(this.contextName(0) + ' != null ? ' + this.contextName(0) + ' : {}');

  return {
    params: params,
    paramsInit: paramsInit,
    name: foundHelper,
    callParams: [callContext].concat(params)
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.setupHelperArgs"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>setupHelperArgs (helper, paramSize, params, useRegister)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.setupHelperArgs)
- description and source-code
```javascript
function setupHelperArgs(helper, paramSize, params, useRegister) {
  var options = this.setupParams(helper, paramSize, params);
  options = this.objectLiteral(options);
  if (useRegister) {
    this.useRegister('options');
    params.push('options');
    return ['options=', options];
  } else if (params) {
    params.push(options);
    return '';
  } else {
    return options;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.setupParams"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>setupParams (helper, paramSize, params)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.setupParams)
- description and source-code
```javascript
function setupParams(helper, paramSize, params) {
  var options = {},
      contexts = [],
      types = [],
      ids = [],
      objectArgs = !params,
      param = undefined;

  if (objectArgs) {
    params = [];
  }

  options.name = this.quotedString(helper);
  options.hash = this.popStack();

  if (this.trackIds) {
    options.hashIds = this.popStack();
  }
  if (this.stringParams) {
    options.hashTypes = this.popStack();
    options.hashContexts = this.popStack();
  }

  var inverse = this.popStack(),
      program = this.popStack();

  // Avoid setting fn and inverse if neither are set. This allows
  // helpers to do a check for 'if (options.fn)'
  if (program || inverse) {
    options.fn = program || 'container.noop';
    options.inverse = inverse || 'container.noop';
  }

  // The parameters go on to the stack in order (making sure that they are evaluated in order)
  // so we need to pop them off the stack in reverse order
  var i = paramSize;
  while (i--) {
    param = this.popStack();
    params[i] = param;

    if (this.trackIds) {
      ids[i] = this.popStack();
    }
    if (this.stringParams) {
      types[i] = this.popStack();
      contexts[i] = this.popStack();
    }
  }

  if (objectArgs) {
    options.args = this.source.generateArray(params);
  }

  if (this.trackIds) {
    options.ids = this.source.generateArray(ids);
  }
  if (this.stringParams) {
    options.types = this.source.generateArray(types);
    options.contexts = this.source.generateArray(contexts);
  }

  if (this.options.data) {
    options.data = 'data';
  }
  if (this.useBlockParams) {
    options.blockParams = 'blockParams';
  }
  return options;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.topStack"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>topStack ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.topStack)
- description and source-code
```javascript
function topStack() {
  var stack = this.isInline() ? this.inlineStack : this.compileStack,
      item = stack[stack.length - 1];

<span class="apidocCodeCommentSpan">  /* istanbul ignore if */
</span>  if (item instanceof Literal) {
    return item.value;
  } else {
    return item;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.topStackName"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>topStackName ()](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.topStackName)
- description and source-code
```javascript
function topStackName() {
  return 'stack' + this.stackSlot;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.useRegister"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.</span>useRegister (name)](#apidoc.element.gulp-compile-handlebars.Handlebars.JavaScriptCompiler.prototype.useRegister)
- description and source-code
```javascript
function useRegister(name) {
  if (!this.registers[name]) {
    this.registers[name] = true;
    this.registers.list.push(name);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-compile-handlebars.Handlebars.PrintVisitor"></a>[module gulp-compile-handlebars.Handlebars.PrintVisitor](#apidoc.module.gulp-compile-handlebars.Handlebars.PrintVisitor)

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.PrintVisitor"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>PrintVisitor ()](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.PrintVisitor)
- description and source-code
```javascript
function PrintVisitor() {
  this.padding = 0;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype"></a>[module gulp-compile-handlebars.Handlebars.PrintVisitor.prototype](#apidoc.module.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype)

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.BlockStatement"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>BlockStatement (block)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.BlockStatement)
- description and source-code
```javascript
BlockStatement = function (block) {
  var out = '';

  out += this.pad((block.type === 'DecoratorBlock' ? 'DIRECTIVE ' : '') + 'BLOCK:');
  this.padding++;
  out += this.pad(this.SubExpression(block));
  if (block.program) {
    out += this.pad('PROGRAM:');
    this.padding++;
    out += this.accept(block.program);
    this.padding--;
  }
  if (block.inverse) {
    if (block.program) {
      this.padding++;
    }
    out += this.pad('{{^}}');
    this.padding++;
    out += this.accept(block.inverse);
    this.padding--;
    if (block.program) {
      this.padding--;
    }
  }
  this.padding--;

  return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.BooleanLiteral"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>BooleanLiteral (bool)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.BooleanLiteral)
- description and source-code
```javascript
BooleanLiteral = function (bool) {
  return 'BOOLEAN{' + bool.value + '}';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.CommentStatement"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>CommentStatement (comment)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.CommentStatement)
- description and source-code
```javascript
CommentStatement = function (comment) {
  return this.pad("{{! '" + comment.value + "' }}");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.ContentStatement"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>ContentStatement (content)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.ContentStatement)
- description and source-code
```javascript
ContentStatement = function (content) {
  return this.pad("CONTENT[ '" + content.value + "' ]");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.Decorator"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>Decorator (mustache)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.Decorator)
- description and source-code
```javascript
Decorator = function (mustache) {
  return this.pad('{{ DIRECTIVE ' + this.SubExpression(mustache) + ' }}');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.DecoratorBlock"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>DecoratorBlock (block)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.DecoratorBlock)
- description and source-code
```javascript
DecoratorBlock = function (block) {
  var out = '';

  out += this.pad((block.type === 'DecoratorBlock' ? 'DIRECTIVE ' : '') + 'BLOCK:');
  this.padding++;
  out += this.pad(this.SubExpression(block));
  if (block.program) {
    out += this.pad('PROGRAM:');
    this.padding++;
    out += this.accept(block.program);
    this.padding--;
  }
  if (block.inverse) {
    if (block.program) {
      this.padding++;
    }
    out += this.pad('{{^}}');
    this.padding++;
    out += this.accept(block.inverse);
    this.padding--;
    if (block.program) {
      this.padding--;
    }
  }
  this.padding--;

  return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.Hash"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>Hash (hash)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.Hash)
- description and source-code
```javascript
Hash = function (hash) {
  var pairs = hash.pairs,
      joinedPairs = [];

  for (var i = 0, l = pairs.length; i < l; i++) {
    joinedPairs.push(this.accept(pairs[i]));
  }

  return 'HASH{' + joinedPairs.join(', ') + '}';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.HashPair"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>HashPair (pair)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.HashPair)
- description and source-code
```javascript
HashPair = function (pair) {
  return pair.key + '=' + this.accept(pair.value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.MustacheStatement"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>MustacheStatement (mustache)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.MustacheStatement)
- description and source-code
```javascript
MustacheStatement = function (mustache) {
  return this.pad('{{ ' + this.SubExpression(mustache) + ' }}');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.NullLiteral"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>NullLiteral ()](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.NullLiteral)
- description and source-code
```javascript
NullLiteral = function () {
  return 'NULL';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.NumberLiteral"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>NumberLiteral (number)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.NumberLiteral)
- description and source-code
```javascript
NumberLiteral = function (number) {
  return 'NUMBER{' + number.value + '}';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.PartialBlockStatement"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>PartialBlockStatement (partial)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.PartialBlockStatement)
- description and source-code
```javascript
PartialBlockStatement = function (partial) {
  var content = 'PARTIAL BLOCK:' + partial.name.original;
  if (partial.params[0]) {
    content += ' ' + this.accept(partial.params[0]);
  }
  if (partial.hash) {
    content += ' ' + this.accept(partial.hash);
  }

  content += ' ' + this.pad('PROGRAM:');
  this.padding++;
  content += this.accept(partial.program);
  this.padding--;

  return this.pad('{{> ' + content + ' }}');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.PartialStatement"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>PartialStatement (partial)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.PartialStatement)
- description and source-code
```javascript
PartialStatement = function (partial) {
  var content = 'PARTIAL:' + partial.name.original;
  if (partial.params[0]) {
    content += ' ' + this.accept(partial.params[0]);
  }
  if (partial.hash) {
    content += ' ' + this.accept(partial.hash);
  }
  return this.pad('{{> ' + content + ' }}');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.PathExpression"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>PathExpression (id)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.PathExpression)
- description and source-code
```javascript
PathExpression = function (id) {
  var path = id.parts.join('/');
  return (id.data ? '@' : '') + 'PATH:' + path;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.Program"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>Program (program)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.Program)
- description and source-code
```javascript
Program = function (program) {
  var out = '',
      body = program.body,
      i = undefined,
      l = undefined;

  if (program.blockParams) {
    var blockParams = 'BLOCK PARAMS: [';
    for (i = 0, l = program.blockParams.length; i < l; i++) {
      blockParams += ' ' + program.blockParams[i];
    }
    blockParams += ' ]';
    out += this.pad(blockParams);
  }

  for (i = 0, l = body.length; i < l; i++) {
    out += this.accept(body[i]);
  }

  this.padding--;

  return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.StringLiteral"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>StringLiteral (string)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.StringLiteral)
- description and source-code
```javascript
StringLiteral = function (string) {
  return '"' + string.value + '"';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.SubExpression"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>SubExpression (sexpr)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.SubExpression)
- description and source-code
```javascript
SubExpression = function (sexpr) {
  var params = sexpr.params,
      paramStrings = [],
      hash = undefined;

  for (var i = 0, l = params.length; i < l; i++) {
    paramStrings.push(this.accept(params[i]));
  }

  params = '[' + paramStrings.join(', ') + ']';

  hash = sexpr.hash ? ' ' + this.accept(sexpr.hash) : '';

  return this.accept(sexpr.path) + ' ' + params + hash;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.UndefinedLiteral"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>UndefinedLiteral ()](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.UndefinedLiteral)
- description and source-code
```javascript
UndefinedLiteral = function () {
  return 'UNDEFINED';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.pad"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.</span>pad (string)](#apidoc.element.gulp-compile-handlebars.Handlebars.PrintVisitor.prototype.pad)
- description and source-code
```javascript
pad = function (string) {
  var out = '';

  for (var i = 0, l = this.padding; i < l; i++) {
    out += '  ';
  }

  out += string + '\n';
  return out;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-compile-handlebars.Handlebars.SafeString"></a>[module gulp-compile-handlebars.Handlebars.SafeString](#apidoc.module.gulp-compile-handlebars.Handlebars.SafeString)

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.SafeString.SafeString"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>SafeString (string)](#apidoc.element.gulp-compile-handlebars.Handlebars.SafeString.SafeString)
- description and source-code
```javascript
function SafeString(string) {
  this.string = string;
}
```
- example usage
```shell
...

## handlebars.Handlebars

You can access the Handlebars library from the 'handlebars.Handlebars' property.

'''js
var handlebars = require('gulp-compile-handlebars');
var safestring = new handlebars.Handlebars.SafeString('<strong>HELLO! KAANON</strong>');
'''

## handlebars.Handlebars

You can access the Handlebars library from the 'handlebars.Handlebars' property.

'''js
...
```



# <a name="apidoc.module.gulp-compile-handlebars.Handlebars.SafeString.prototype"></a>[module gulp-compile-handlebars.Handlebars.SafeString.prototype](#apidoc.module.gulp-compile-handlebars.Handlebars.SafeString.prototype)

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.SafeString.prototype.toHTML"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.SafeString.prototype.</span>toHTML ()](#apidoc.element.gulp-compile-handlebars.Handlebars.SafeString.prototype.toHTML)
- description and source-code
```javascript
toHTML = function () {
  return '' + this.string;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.SafeString.prototype.toString"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.SafeString.prototype.</span>toString ()](#apidoc.element.gulp-compile-handlebars.Handlebars.SafeString.prototype.toString)
- description and source-code
```javascript
toString = function () {
  return '' + this.string;
}
```
- example usage
```shell
...

		if (file.isStream()) {
			this.emit('error', new gutil.PluginError('gulp-compile-handlebars', 'Streaming not supported'));
			return cb();
		}

		try {
			var fileContents = file.contents.toString();
			if(options.ignorePartials){
				mockPartials(fileContents);
			}

			// Enable gulp-data usage, Extend default data with data from file.data
			if(file.data){
				_data = extend(_data, file.data);
...
```



# <a name="apidoc.module.gulp-compile-handlebars.Handlebars.Utils"></a>[module gulp-compile-handlebars.Handlebars.Utils](#apidoc.module.gulp-compile-handlebars.Handlebars.Utils)

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Utils.appendContextPath"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Utils.</span>appendContextPath (contextPath, id)](#apidoc.element.gulp-compile-handlebars.Handlebars.Utils.appendContextPath)
- description and source-code
```javascript
function appendContextPath(contextPath, id) {
  return (contextPath ? contextPath + '.' : '') + id;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Utils.blockParams"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Utils.</span>blockParams (params, ids)](#apidoc.element.gulp-compile-handlebars.Handlebars.Utils.blockParams)
- description and source-code
```javascript
function blockParams(params, ids) {
  params.path = ids;
  return params;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Utils.createFrame"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Utils.</span>createFrame (object)](#apidoc.element.gulp-compile-handlebars.Handlebars.Utils.createFrame)
- description and source-code
```javascript
function createFrame(object) {
  var frame = extend({}, object);
  frame._parent = object;
  return frame;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Utils.escapeExpression"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Utils.</span>escapeExpression (string)](#apidoc.element.gulp-compile-handlebars.Handlebars.Utils.escapeExpression)
- description and source-code
```javascript
function escapeExpression(string) {
  if (typeof string !== 'string') {
    // don't escape SafeStrings, since they're already safe
    if (string && string.toHTML) {
      return string.toHTML();
    } else if (string == null) {
      return '';
    } else if (!string) {
      return string + '';
    }

    // Force a string conversion as this will be done by the append regardless and
    // the regex test will do this transparently behind the scenes, causing issues if
    // an object's to string has escaped characters in it.
    string = '' + string;
  }

  if (!possible.test(string)) {
    return string;
  }
  return string.replace(badChars, escapeChar);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Utils.extend"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Utils.</span>extend (obj)](#apidoc.element.gulp-compile-handlebars.Handlebars.Utils.extend)
- description and source-code
```javascript
function extend(obj) {
  for (var i = 1; i < arguments.length; i++) {
    for (var key in arguments[i]) {
      if (Object.prototype.hasOwnProperty.call(arguments[i], key)) {
        obj[key] = arguments[i][key];
      }
    }
  }

  return obj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Utils.indexOf"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Utils.</span>indexOf (array, value)](#apidoc.element.gulp-compile-handlebars.Handlebars.Utils.indexOf)
- description and source-code
```javascript
function indexOf(array, value) {
  for (var i = 0, len = array.length; i < len; i++) {
    if (array[i] === value) {
      return i;
    }
  }
  return -1;
}
```
- example usage
```shell
...

	var isDir = function (filename) {
		var stats = fs.statSync(filename);
		return stats && stats.isDirectory();
	};

	var isHandlebars = function (filename) {
		return allowedExtensions.indexOf(filename.split('.').pop()) !== -1;
	};

	var partialName = function (filename, base) {
		var name = path.join(path.dirname(filename), path.basename(filename, path.extname(filename)));
		if (name.indexOf(base) === 0) {
			name = name.slice(base.length);
		}
...
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Utils.isArray"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Utils.</span>isArray ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Utils.isArray)
- description and source-code
```javascript
function isArray() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Utils.isEmpty"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Utils.</span>isEmpty (value)](#apidoc.element.gulp-compile-handlebars.Handlebars.Utils.isEmpty)
- description and source-code
```javascript
function isEmpty(value) {
  if (!value && value !== 0) {
    return true;
  } else if (isArray(value) && value.length === 0) {
    return true;
  } else {
    return false;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Utils.isFunction"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Utils.</span>isFunction (value)](#apidoc.element.gulp-compile-handlebars.Handlebars.Utils.isFunction)
- description and source-code
```javascript
function isFunction(value) {
  return typeof value === 'function';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-compile-handlebars.Handlebars.VM"></a>[module gulp-compile-handlebars.Handlebars.VM](#apidoc.module.gulp-compile-handlebars.Handlebars.VM)

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.VM.checkRevision"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.VM.</span>checkRevision (compilerInfo)](#apidoc.element.gulp-compile-handlebars.Handlebars.VM.checkRevision)
- description and source-code
```javascript
function checkRevision(compilerInfo) {
  var compilerRevision = compilerInfo && compilerInfo[0] || 1,
      currentRevision = _base.COMPILER_REVISION;

  if (compilerRevision !== currentRevision) {
    if (compilerRevision < currentRevision) {
      var runtimeVersions = _base.REVISION_CHANGES[currentRevision],
          compilerVersions = _base.REVISION_CHANGES[compilerRevision];
      throw new _exception2['default']('Template was precompiled with an older version of Handlebars than the current runtime. ' + '
Please update your precompiler to a newer version (' + runtimeVersions + ') or downgrade your runtime to an older version (' + compilerVersions
 + ').');
    } else {
      // Use the embedded version info since the runtime doesn't know about this revision yet
      throw new _exception2['default']('Template was precompiled with a newer version of Handlebars than the current runtime. ' + '
Please update your runtime to a newer version (' + compilerInfo[1] + ').');
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.VM.invokePartial"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.VM.</span>invokePartial (partial, context, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.VM.invokePartial)
- description and source-code
```javascript
function invokePartial(partial, context, options) {
  options.partial = true;
  if (options.ids) {
    options.data.contextPath = options.ids[0] || options.data.contextPath;
  }

  var partialBlock = undefined;
  if (options.fn && options.fn !== noop) {
    options.data = _base.createFrame(options.data);
    partialBlock = options.data['partial-block'] = options.fn;

    if (partialBlock.partials) {
      options.partials = Utils.extend({}, options.partials, partialBlock.partials);
    }
  }

  if (partial === undefined && partialBlock) {
    partial = partialBlock;
  }

  if (partial === undefined) {
    throw new _exception2['default']('The partial ' + options.name + ' could not be found');
  } else if (partial instanceof Function) {
    return partial(context, options);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.VM.noop"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.VM.</span>noop ()](#apidoc.element.gulp-compile-handlebars.Handlebars.VM.noop)
- description and source-code
```javascript
function noop() {
  return '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.VM.resolvePartial"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.VM.</span>resolvePartial (partial, context, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.VM.resolvePartial)
- description and source-code
```javascript
function resolvePartial(partial, context, options) {
  if (!partial) {
    if (options.name === '@partial-block') {
      var data = options.data;
      while (data['partial-block'] === noop) {
        data = data._parent;
      }
      partial = data['partial-block'];
      data['partial-block'] = noop;
    } else {
      partial = options.partials[options.name];
    }
  } else if (!partial.call && !options.name) {
    // This is a dynamic partial that returned a string
    options.name = partial;
    partial = options.partials[partial];
  }
  return partial;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.VM.template"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.VM.</span>template (templateSpec, env)](#apidoc.element.gulp-compile-handlebars.Handlebars.VM.template)
- description and source-code
```javascript
function template(templateSpec, env) {
<span class="apidocCodeCommentSpan">  /* istanbul ignore next */
</span>  if (!env) {
    throw new _exception2['default']('No environment passed to template');
  }
  if (!templateSpec || !templateSpec.main) {
    throw new _exception2['default']('Unknown template object: ' + typeof templateSpec);
  }

  templateSpec.main.decorator = templateSpec.main_d;

  // Note: Using env.VM references rather than local var references throughout this section to allow
  // for external users to override these as psuedo-supported APIs.
  env.VM.checkRevision(templateSpec.compiler);

  function invokePartialWrapper(partial, context, options) {
    if (options.hash) {
      context = Utils.extend({}, context, options.hash);
      if (options.ids) {
        options.ids[0] = true;
      }
    }

    partial = env.VM.resolvePartial.call(this, partial, context, options);
    var result = env.VM.invokePartial.call(this, partial, context, options);

    if (result == null && env.compile) {
      options.partials[options.name] = env.compile(partial, templateSpec.compilerOptions, env);
      result = options.partials[options.name](context, options);
    }
    if (result != null) {
      if (options.indent) {
        var lines = result.split('\n');
        for (var i = 0, l = lines.length; i < l; i++) {
          if (!lines[i] && i + 1 === l) {
            break;
          }

          lines[i] = options.indent + lines[i];
        }
        result = lines.join('\n');
      }
      return result;
    } else {
      throw new _exception2['default']('The partial ' + options.name + ' could not be compiled when running in runtime-only mode
');
    }
  }

  // Just add water
  var container = {
    strict: function strict(obj, name) {
      if (!(name in obj)) {
        throw new _exception2['default']('"' + name + '" not defined in ' + obj);
      }
      return obj[name];
    },
    lookup: function lookup(depths, name) {
      var len = depths.length;
      for (var i = 0; i < len; i++) {
        if (depths[i] && depths[i][name] != null) {
          return depths[i][name];
        }
      }
    },
    lambda: function lambda(current, context) {
      return typeof current === 'function' ? current.call(context) : current;
    },

    escapeExpression: Utils.escapeExpression,
    invokePartial: invokePartialWrapper,

    fn: function fn(i) {
      var ret = templateSpec[i];
      ret.decorator = templateSpec[i + '_d'];
      return ret;
    },

    programs: [],
    program: function program(i, data, declaredBlockParams, blockParams, depths) {
      var programWrapper = this.programs[i],
          fn = this.fn(i);
      if (data || depths || blockParams || declaredBlockParams) {
        programWrapper = wrapProgram(this, i, fn, data, declaredBlockParams, blockParams, depths);
      } else if (!programWrapper) {
        programWrapper = this.programs[i] = wrapProgram(this, i, fn);
      }
      return programWrapper;
    },

    data: function data(value, depth) {
      while (value && depth--) {
        value = value._parent;
      }
      return value;
    },
    merge: function merge(param, common) {
      var obj = param || common;

      if (param && common && param !== common) {
        obj = Utils.extend({}, common, param);
      }

      return obj;
    },

    noop: env.VM.noop,
    compilerInfo: templateSpec.compiler
  };

  function ret(context) {
    var options = arguments.length <= 1 || arguments[1] === undefined ? {} : arguments[1];

    var data = options.data;

    ret._setup(options);
    if (!options.partial && templateSpec.useData) {
      data = initData(context, data);
    }
    var depths = undefined,
        blockParams = templateSpec.useBlockParams ? [] : undefined;
    if (templateSpec.useDepths) {
      if (options.depths) {
        depths = context != options.depths[0] ? [context].concat(options.depths) : options.depths;
      } else {
        depths = [context];
      }
    }

    function main(context /*, options*/) {
      return '' + templateSpec.main(container, context, container.helpers, container.partials, data, blockPara ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.VM.wrapProgram"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.VM.</span>wrapProgram (container, i, fn, data, declaredBlockParams, blockParams, depths)](#apidoc.element.gulp-compile-handlebars.Handlebars.VM.wrapProgram)
- description and source-code
```javascript
function wrapProgram(container, i, fn, data, declaredBlockParams, blockParams, depths) {
  function prog(context) {
    var options = arguments.length <= 1 || arguments[1] === undefined ? {} : arguments[1];

    var currentDepths = depths;
    if (depths && context != depths[0]) {
      currentDepths = [context].concat(depths);
    }

    return fn(container, context, container.helpers, container.partials, options.data || data, blockParams && [options.blockParams
].concat(blockParams), currentDepths);
  }

  prog = executeDecorators(fn, prog, container, depths, data, blockParams);

  prog.program = i;
  prog.depth = depths ? depths.length : 0;
  prog.blockParams = declaredBlockParams || 0;
  return prog;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-compile-handlebars.Handlebars.Visitor"></a>[module gulp-compile-handlebars.Handlebars.Visitor](#apidoc.module.gulp-compile-handlebars.Handlebars.Visitor)

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.Visitor"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.</span>Visitor ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.Visitor)
- description and source-code
```javascript
function Visitor() {
  this.parents = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-compile-handlebars.Handlebars.Visitor.prototype"></a>[module gulp-compile-handlebars.Handlebars.Visitor.prototype](#apidoc.module.gulp-compile-handlebars.Handlebars.Visitor.prototype)

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.BlockStatement"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>BlockStatement (block)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.BlockStatement)
- description and source-code
```javascript
function visitBlock(block) {
  visitSubExpression.call(this, block);

  this.acceptKey(block, 'program');
  this.acceptKey(block, 'inverse');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.BooleanLiteral"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>BooleanLiteral ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.BooleanLiteral)
- description and source-code
```javascript
function BooleanLiteral() /* bool */{}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.CommentStatement"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>CommentStatement ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.CommentStatement)
- description and source-code
```javascript
function CommentStatement() /* comment */{}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.ContentStatement"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>ContentStatement ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.ContentStatement)
- description and source-code
```javascript
function ContentStatement() /* content */{}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.Decorator"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>Decorator (mustache)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.Decorator)
- description and source-code
```javascript
function visitSubExpression(mustache) {
  this.acceptRequired(mustache, 'path');
  this.acceptArray(mustache.params);
  this.acceptKey(mustache, 'hash');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.DecoratorBlock"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>DecoratorBlock (block)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.DecoratorBlock)
- description and source-code
```javascript
function visitBlock(block) {
  visitSubExpression.call(this, block);

  this.acceptKey(block, 'program');
  this.acceptKey(block, 'inverse');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.Hash"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>Hash (hash)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.Hash)
- description and source-code
```javascript
function Hash(hash) {
  this.acceptArray(hash.pairs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.HashPair"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>HashPair (pair)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.HashPair)
- description and source-code
```javascript
function HashPair(pair) {
  this.acceptRequired(pair, 'value');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.MustacheStatement"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>MustacheStatement (mustache)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.MustacheStatement)
- description and source-code
```javascript
function visitSubExpression(mustache) {
  this.acceptRequired(mustache, 'path');
  this.acceptArray(mustache.params);
  this.acceptKey(mustache, 'hash');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.NullLiteral"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>NullLiteral ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.NullLiteral)
- description and source-code
```javascript
function NullLiteral() /* literal */{}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.NumberLiteral"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>NumberLiteral ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.NumberLiteral)
- description and source-code
```javascript
function NumberLiteral() /* number */{}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.PartialBlockStatement"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>PartialBlockStatement (partial)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.PartialBlockStatement)
- description and source-code
```javascript
function PartialBlockStatement(partial) {
  visitPartial.call(this, partial);

  this.acceptKey(partial, 'program');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.PartialStatement"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>PartialStatement (partial)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.PartialStatement)
- description and source-code
```javascript
function visitPartial(partial) {
  this.acceptRequired(partial, 'name');
  this.acceptArray(partial.params);
  this.acceptKey(partial, 'hash');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.PathExpression"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>PathExpression ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.PathExpression)
- description and source-code
```javascript
function PathExpression() /* path */{}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.Program"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>Program (program)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.Program)
- description and source-code
```javascript
function Program(program) {
  this.acceptArray(program.body);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.StringLiteral"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>StringLiteral ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.StringLiteral)
- description and source-code
```javascript
function StringLiteral() /* string */{}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.SubExpression"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>SubExpression (mustache)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.SubExpression)
- description and source-code
```javascript
function visitSubExpression(mustache) {
  this.acceptRequired(mustache, 'path');
  this.acceptArray(mustache.params);
  this.acceptKey(mustache, 'hash');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.UndefinedLiteral"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>UndefinedLiteral ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.UndefinedLiteral)
- description and source-code
```javascript
function UndefinedLiteral() /* literal */{}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.accept"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>accept (object)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.accept)
- description and source-code
```javascript
function accept(object) {
  if (!object) {
    return;
  }

<span class="apidocCodeCommentSpan">  /* istanbul ignore next: Sanity code */
</span>  if (!this[object.type]) {
    throw new _exception2['default']('Unknown type: ' + object.type, object);
  }

  if (this.current) {
    this.parents.unshift(this.current);
  }
  this.current = object;

  var ret = this[object.type](object);

  this.current = this.parents.shift();

  if (!this.mutating || ret) {
    return ret;
  } else if (ret !== false) {
    return object;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.acceptArray"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>acceptArray (array)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.acceptArray)
- description and source-code
```javascript
function acceptArray(array) {
  for (var i = 0, l = array.length; i < l; i++) {
    this.acceptKey(array, i);

    if (!array[i]) {
      array.splice(i, 1);
      i--;
      l--;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.acceptKey"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>acceptKey (node, name)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.acceptKey)
- description and source-code
```javascript
function acceptKey(node, name) {
  var value = this.accept(node[name]);
  if (this.mutating) {
    // Hacky sanity check: This may have a few false positives for type for the helper
    // methods but will generally do the right thing without a lot of overhead.
    if (value && !Visitor.prototype[value.type]) {
      throw new _exception2['default']('Unexpected node type "' + value.type + '" found when accepting ' + name + ' on ' + node.
type);
    }
    node[name] = value;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.acceptRequired"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>acceptRequired (node, name)](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.acceptRequired)
- description and source-code
```javascript
function acceptRequired(node, name) {
  this.acceptKey(node, name);

  if (!node[name]) {
    throw new _exception2['default'](node.type + ' requires ' + name);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.Visitor.prototype.</span>constructor ()](#apidoc.element.gulp-compile-handlebars.Handlebars.Visitor.prototype.constructor)
- description and source-code
```javascript
function Visitor() {
  this.parents = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-compile-handlebars.Handlebars.decorators"></a>[module gulp-compile-handlebars.Handlebars.decorators](#apidoc.module.gulp-compile-handlebars.Handlebars.decorators)

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.decorators.inline"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.decorators.</span>inline (fn, props, container, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.decorators.inline)
- description and source-code
```javascript
inline = function (fn, props, container, options) {
  var ret = fn;
  if (!props.partials) {
    props.partials = {};
    ret = function (context, options) {
      // Create a new partials stack frame prior to exec.
      var original = container.partials;
      container.partials = _utils.extend({}, original, props.partials);
      var ret = fn(context, options);
      container.partials = original;
      return ret;
    };
  }

  props.partials[options.args[0]] = options.fn;

  return ret;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-compile-handlebars.Handlebars.helpers"></a>[module gulp-compile-handlebars.Handlebars.helpers](#apidoc.module.gulp-compile-handlebars.Handlebars.helpers)

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.helpers.blockHelperMissing"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.helpers.</span>blockHelperMissing (context, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.helpers.blockHelperMissing)
- description and source-code
```javascript
blockHelperMissing = function (context, options) {
  var inverse = options.inverse,
      fn = options.fn;

  if (context === true) {
    return fn(this);
  } else if (context === false || context == null) {
    return inverse(this);
  } else if (_utils.isArray(context)) {
    if (context.length > 0) {
      if (options.ids) {
        options.ids = [options.name];
      }

      return instance.helpers.each(context, options);
    } else {
      return inverse(this);
    }
  } else {
    if (options.data && options.ids) {
      var data = _utils.createFrame(options.data);
      data.contextPath = _utils.appendContextPath(options.data.contextPath, options.name);
      options = { data: data };
    }

    return fn(context, options);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.helpers.each"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.helpers.</span>each (context, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.helpers.each)
- description and source-code
```javascript
each = function (context, options) {
  if (!options) {
    throw new _exception2['default']('Must pass iterator to #each');
  }

  var fn = options.fn,
      inverse = options.inverse,
      i = 0,
      ret = '',
      data = undefined,
      contextPath = undefined;

  if (options.data && options.ids) {
    contextPath = _utils.appendContextPath(options.data.contextPath, options.ids[0]) + '.';
  }

  if (_utils.isFunction(context)) {
    context = context.call(this);
  }

  if (options.data) {
    data = _utils.createFrame(options.data);
  }

  function execIteration(field, index, last) {
    if (data) {
      data.key = field;
      data.index = index;
      data.first = index === 0;
      data.last = !!last;

      if (contextPath) {
        data.contextPath = contextPath + field;
      }
    }

    ret = ret + fn(context[field], {
      data: data,
      blockParams: _utils.blockParams([context[field], field], [contextPath + field, null])
    });
  }

  if (context && typeof context === 'object') {
    if (_utils.isArray(context)) {
      for (var j = context.length; i < j; i++) {
        if (i in context) {
          execIteration(i, i, i === context.length - 1);
        }
      }
    } else {
      var priorKey = undefined;

      for (var key in context) {
        if (context.hasOwnProperty(key)) {
          // We're running the iterations one step out of sync so we can detect
          // the last iteration without have to scan the object twice and create
          // an itermediate keys array.
          if (priorKey !== undefined) {
            execIteration(priorKey, i - 1);
          }
          priorKey = key;
          i++;
        }
      }
      if (priorKey !== undefined) {
        execIteration(priorKey, i - 1, true);
      }
    }
  }

  if (i === 0) {
    ret = inverse(this);
  }

  return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.helpers.helperMissing"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.helpers.</span>helperMissing ()](#apidoc.element.gulp-compile-handlebars.Handlebars.helpers.helperMissing)
- description and source-code
```javascript
helperMissing = function () /* [args, ]options */{
  if (arguments.length === 1) {
    // A missing field in a {{foo}} construct.
    return undefined;
  } else {
    // Someone is actually trying to call something, blow up.
    throw new _exception2['default']('Missing helper: "' + arguments[arguments.length - 1].name + '"');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.helpers.if"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.helpers.</span>if (conditional, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.helpers.if)
- description and source-code
```javascript
if = function (conditional, options) {
  if (_utils.isFunction(conditional)) {
    conditional = conditional.call(this);
  }

  // Default behavior is to render the positive path if the value is truthy and not empty.
  // The 'includeZero' option may be set to treat the condtional as purely not empty based on the
  // behavior of isEmpty. Effectively this determines if 0 is handled by the positive path or negative.
  if (!options.hash.includeZero && !conditional || _utils.isEmpty(conditional)) {
    return options.inverse(this);
  } else {
    return options.fn(this);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.helpers.log"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.helpers.</span>log ()](#apidoc.element.gulp-compile-handlebars.Handlebars.helpers.log)
- description and source-code
```javascript
log = function () /* message, options */{
  var args = [undefined],
      options = arguments[arguments.length - 1];
  for (var i = 0; i < arguments.length - 1; i++) {
    args.push(arguments[i]);
  }

  var level = 1;
  if (options.hash.level != null) {
    level = options.hash.level;
  } else if (options.data && options.data.level != null) {
    level = options.data.level;
  }
  args[0] = level;

  instance.log.apply(instance, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.helpers.lookup"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.helpers.</span>lookup (obj, field)](#apidoc.element.gulp-compile-handlebars.Handlebars.helpers.lookup)
- description and source-code
```javascript
lookup = function (obj, field) {
  return obj && obj[field];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.helpers.unless"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.helpers.</span>unless (conditional, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.helpers.unless)
- description and source-code
```javascript
unless = function (conditional, options) {
  return instance.helpers['if'].call(this, conditional, { fn: options.inverse, inverse: options.fn, hash: options.hash });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.helpers.with"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.helpers.</span>with (context, options)](#apidoc.element.gulp-compile-handlebars.Handlebars.helpers.with)
- description and source-code
```javascript
with = function (context, options) {
  if (_utils.isFunction(context)) {
    context = context.call(this);
  }

  var fn = options.fn;

  if (!_utils.isEmpty(context)) {
    var data = options.data;
    if (options.data && options.ids) {
      data = _utils.createFrame(options.data);
      data.contextPath = _utils.appendContextPath(options.data.contextPath, options.ids[0]);
    }

    return fn(context, {
      data: data,
      blockParams: _utils.blockParams([context], [data && data.contextPath])
    });
  } else {
    return options.inverse(this);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-compile-handlebars.Handlebars.logger"></a>[module gulp-compile-handlebars.Handlebars.logger](#apidoc.module.gulp-compile-handlebars.Handlebars.logger)

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.logger.log"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.logger.</span>log (level)](#apidoc.element.gulp-compile-handlebars.Handlebars.logger.log)
- description and source-code
```javascript
function log(level) {
  level = logger.lookupLevel(level);

  if (typeof console !== 'undefined' && logger.lookupLevel(logger.level) <= level) {
    var method = logger.methodMap[level];
    if (!console[method]) {
      // eslint-disable-line no-console
      method = 'log';
    }

    for (var _len = arguments.length, message = Array(_len > 1 ? _len - 1 : 0), _key = 1; _key < _len; _key++) {
      message[_key - 1] = arguments[_key];
    }

    console[method].apply(console, message); // eslint-disable-line no-console
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-compile-handlebars.Handlebars.logger.lookupLevel"></a>[function <span class="apidocSignatureSpan">gulp-compile-handlebars.Handlebars.logger.</span>lookupLevel (level)](#apidoc.element.gulp-compile-handlebars.Handlebars.logger.lookupLevel)
- description and source-code
```javascript
function lookupLevel(level) {
  if (typeof level === 'string') {
    var levelMap = _utils.indexOf(logger.methodMap, level.toLowerCase());
    if (levelMap >= 0) {
      level = levelMap;
    } else {
      level = parseInt(level, 10);
    }
  }

  return level;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
