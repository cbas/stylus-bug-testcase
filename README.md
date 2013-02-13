Version:

    stylus --version
    0.31.0

Command:

    stylus app.styl

Error:

    /usr/local/lib/node_modules/stylus/bin/stylus:516
                  throw err;
                        ^
    CoercionError: layout.styl:2
       1| header
     > 2| 	width $pageWidth + 50px
       3|

    cannot coerce 50px to ident
        at "header" (layout.styl:2)

        at Ident.Node.coerce (/usr/local/lib/node_modules/stylus/lib/nodes/node.js:222:9)
        at Ident.coerce (/usr/local/lib/node_modules/stylus/lib/nodes/ident.js:99:36)
        at Ident.operate (/usr/local/lib/node_modules/stylus/lib/nodes/ident.js:124:49)
        at Evaluator.visitBinOp (/usr/local/lib/node_modules/stylus/lib/visitor/evaluator.js:417:28)
        at Evaluator.Visitor.visit (/usr/local/lib/node_modules/stylus/lib/visitor/index.js:28:40)
        at Evaluator.visit (/usr/local/lib/node_modules/stylus/lib/visitor/evaluator.js:75:18)
        at Evaluator.visitExpression (/usr/local/lib/node_modules/stylus/lib/visitor/evaluator.js:480:26)
        at Evaluator.Visitor.visit (/usr/local/lib/node_modules/stylus/lib/visitor/index.js:28:40)
        at Evaluator.visit (/usr/local/lib/node_modules/stylus/lib/visitor/evaluator.js:75:18)
        at Evaluator.visitExpression (/usr/local/lib/node_modules/stylus/lib/visitor/evaluator.js:480:26)
