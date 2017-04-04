# api documentation for  [eslint-plugin-angular (v2.2.1)](https://github.com/Gillespie59/eslint-plugin-angularjs)  [![npm package](https://img.shields.io/npm/v/npmdoc-eslint-plugin-angular.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-eslint-plugin-angular) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-eslint-plugin-angular.svg)](https://travis-ci.org/npmdoc/node-npmdoc-eslint-plugin-angular)
#### ESLint rules for AngularJS projects

[![NPM](https://nodei.co/npm/eslint-plugin-angular.png?downloads=true)](https://www.npmjs.com/package/eslint-plugin-angular)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint-plugin-angular/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-eslint-plugin-angular_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint-plugin-angular/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-eslint-plugin-angular/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-eslint-plugin-angular/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/Gillespie59/eslint-plugin-angularjs/issues"
    },
    "contributors": [
        {
            "name": "Emmanuel Demey",
            "url": "http://gillespie59.github.io/"
        },
        {
            "name": "Tilman Potthof",
            "url": "https://github.com/tilmanpotthof"
        },
        {
            "name": "Remco Haszing",
            "url": "https://github.com/remcohaszing"
        }
    ],
    "dependencies": {},
    "description": "ESLint rules for AngularJS projects",
    "devDependencies": {
        "chai": "^3.5.0",
        "chai-spies": "^0.7.1",
        "coveralls": "^2.11.6",
        "eslint": "^3.18.0",
        "espree": "^3.0.1",
        "gulp": "^3.9.1",
        "gulp-eslint": "^3.0.1",
        "gulp-istanbul": "^1.0.0",
        "gulp-mocha": "^3.0.1",
        "istanbul": "^0.4.2",
        "lodash": "^4.13.1",
        "mocha": "^3.2.0",
        "parse-comments": "^0.4.3",
        "shelljs": "^0.7.1",
        "shelljs-nodecli": "^0.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "2fe426808d675114c5d78c8b25642499053cae92",
        "tarball": "https://registry.npmjs.org/eslint-plugin-angular/-/eslint-plugin-angular-2.2.1.tgz"
    },
    "gitHead": "99a907f27f7e13d41cd033b418d1cd172a2822e7",
    "homepage": "https://github.com/Gillespie59/eslint-plugin-angularjs",
    "keywords": [
        "eslint",
        "eslintplugin",
        "angular",
        "angularjs"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "emmanueldemey",
            "email": "demey.emmanuel@gmail.com"
        }
    ],
    "name": "eslint-plugin-angular",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Gillespie59/eslint-plugin-angularjs.git"
    },
    "scripts": {
        "test": "gulp"
    },
    "version": "2.2.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module eslint-plugin-angular](#apidoc.module.eslint-plugin-angular)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>angularelement
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>component_limit
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>component_name
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>constant_name
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>controller_as
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>controller_as_route
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>controller_as_vm
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>controller_name
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>deferred
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>definedundefined
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>di
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>di_order
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>di_unused
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>directive_name
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>directive_restrict
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>document_service
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>dumb_inject
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>empty_controller
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>environments
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>factory_name
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>file_name
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>filter_name
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>foreach
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>function_type
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>interval_service
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>json_functions
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>module_dependency_order
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>module_getter
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>module_name
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>module_setter
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>no_controller
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>no_cookiestore
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>no_directive_replace
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>no_http_callback
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>no_inline_template
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>no_jquery_angularelement
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>no_private_call
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>no_run_logic
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>no_service_method
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>no_services
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>on_destroy
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>on_watch
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>one_dependency_per_line
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>prefer_component
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>provider_name
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>rest_service
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>rules
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>service_name
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>timeout_service
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>typecheck_array
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>typecheck_date
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>typecheck_function
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>typecheck_number
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>typecheck_object
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>typecheck_string
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>value_name
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>watchers_execution
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.</span>window_service

#### [module eslint-plugin-angular.angularelement](#apidoc.module.eslint-plugin-angular.angularelement)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.angularelement.</span>create (context)](#apidoc.element.eslint-plugin-angular.angularelement.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.angularelement.</span>meta

#### [module eslint-plugin-angular.component_limit](#apidoc.module.eslint-plugin-angular.component_limit)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.component_limit.</span>create (context)](#apidoc.element.eslint-plugin-angular.component_limit.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.component_limit.</span>meta

#### [module eslint-plugin-angular.component_name](#apidoc.module.eslint-plugin-angular.component_name)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.component_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.component_name.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.component_name.</span>meta

#### [module eslint-plugin-angular.constant_name](#apidoc.module.eslint-plugin-angular.constant_name)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.constant_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.constant_name.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.constant_name.</span>meta

#### [module eslint-plugin-angular.controller_as](#apidoc.module.eslint-plugin-angular.controller_as)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.controller_as.</span>create (context)](#apidoc.element.eslint-plugin-angular.controller_as.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.controller_as.</span>meta

#### [module eslint-plugin-angular.controller_as_route](#apidoc.module.eslint-plugin-angular.controller_as_route)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.controller_as_route.</span>create (context)](#apidoc.element.eslint-plugin-angular.controller_as_route.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.controller_as_route.</span>meta

#### [module eslint-plugin-angular.controller_as_vm](#apidoc.module.eslint-plugin-angular.controller_as_vm)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.controller_as_vm.</span>create (context)](#apidoc.element.eslint-plugin-angular.controller_as_vm.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.controller_as_vm.</span>meta

#### [module eslint-plugin-angular.controller_name](#apidoc.module.eslint-plugin-angular.controller_name)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.controller_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.controller_name.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.controller_name.</span>meta

#### [module eslint-plugin-angular.deferred](#apidoc.module.eslint-plugin-angular.deferred)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.deferred.</span>create (context)](#apidoc.element.eslint-plugin-angular.deferred.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.deferred.</span>meta

#### [module eslint-plugin-angular.definedundefined](#apidoc.module.eslint-plugin-angular.definedundefined)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.definedundefined.</span>create (context)](#apidoc.element.eslint-plugin-angular.definedundefined.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.definedundefined.</span>meta

#### [module eslint-plugin-angular.di](#apidoc.module.eslint-plugin-angular.di)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.di.</span>create (context)](#apidoc.element.eslint-plugin-angular.di.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.di.</span>meta

#### [module eslint-plugin-angular.di_order](#apidoc.module.eslint-plugin-angular.di_order)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.di_order.</span>create (context)](#apidoc.element.eslint-plugin-angular.di_order.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.di_order.</span>meta

#### [module eslint-plugin-angular.di_unused](#apidoc.module.eslint-plugin-angular.di_unused)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.di_unused.</span>create (context)](#apidoc.element.eslint-plugin-angular.di_unused.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.di_unused.</span>meta

#### [module eslint-plugin-angular.directive_name](#apidoc.module.eslint-plugin-angular.directive_name)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.directive_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.directive_name.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.directive_name.</span>meta

#### [module eslint-plugin-angular.directive_restrict](#apidoc.module.eslint-plugin-angular.directive_restrict)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.directive_restrict.</span>create (context)](#apidoc.element.eslint-plugin-angular.directive_restrict.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.directive_restrict.</span>meta

#### [module eslint-plugin-angular.document_service](#apidoc.module.eslint-plugin-angular.document_service)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.document_service.</span>create (context)](#apidoc.element.eslint-plugin-angular.document_service.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.document_service.</span>meta

#### [module eslint-plugin-angular.dumb_inject](#apidoc.module.eslint-plugin-angular.dumb_inject)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.dumb_inject.</span>create (context)](#apidoc.element.eslint-plugin-angular.dumb_inject.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.dumb_inject.</span>meta

#### [module eslint-plugin-angular.empty_controller](#apidoc.module.eslint-plugin-angular.empty_controller)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.empty_controller.</span>create (context)](#apidoc.element.eslint-plugin-angular.empty_controller.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.empty_controller.</span>meta

#### [module eslint-plugin-angular.factory_name](#apidoc.module.eslint-plugin-angular.factory_name)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.factory_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.factory_name.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.factory_name.</span>meta

#### [module eslint-plugin-angular.file_name](#apidoc.module.eslint-plugin-angular.file_name)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.file_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.file_name.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.file_name.</span>meta

#### [module eslint-plugin-angular.filter_name](#apidoc.module.eslint-plugin-angular.filter_name)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.filter_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.filter_name.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.filter_name.</span>meta

#### [module eslint-plugin-angular.foreach](#apidoc.module.eslint-plugin-angular.foreach)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.foreach.</span>create (context)](#apidoc.element.eslint-plugin-angular.foreach.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.foreach.</span>meta

#### [module eslint-plugin-angular.function_type](#apidoc.module.eslint-plugin-angular.function_type)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.function_type.</span>create (context)](#apidoc.element.eslint-plugin-angular.function_type.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.function_type.</span>meta

#### [module eslint-plugin-angular.interval_service](#apidoc.module.eslint-plugin-angular.interval_service)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.interval_service.</span>create (context)](#apidoc.element.eslint-plugin-angular.interval_service.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.interval_service.</span>meta

#### [module eslint-plugin-angular.json_functions](#apidoc.module.eslint-plugin-angular.json_functions)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.json_functions.</span>create (context)](#apidoc.element.eslint-plugin-angular.json_functions.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.json_functions.</span>meta

#### [module eslint-plugin-angular.module_dependency_order](#apidoc.module.eslint-plugin-angular.module_dependency_order)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.module_dependency_order.</span>create (context)](#apidoc.element.eslint-plugin-angular.module_dependency_order.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.module_dependency_order.</span>meta

#### [module eslint-plugin-angular.module_getter](#apidoc.module.eslint-plugin-angular.module_getter)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.module_getter.</span>create (context)](#apidoc.element.eslint-plugin-angular.module_getter.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.module_getter.</span>meta

#### [module eslint-plugin-angular.module_name](#apidoc.module.eslint-plugin-angular.module_name)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.module_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.module_name.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.module_name.</span>meta

#### [module eslint-plugin-angular.module_setter](#apidoc.module.eslint-plugin-angular.module_setter)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.module_setter.</span>create (context)](#apidoc.element.eslint-plugin-angular.module_setter.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.module_setter.</span>meta

#### [module eslint-plugin-angular.no_controller](#apidoc.module.eslint-plugin-angular.no_controller)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.no_controller.</span>create (context)](#apidoc.element.eslint-plugin-angular.no_controller.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.no_controller.</span>meta

#### [module eslint-plugin-angular.no_cookiestore](#apidoc.module.eslint-plugin-angular.no_cookiestore)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.no_cookiestore.</span>create (context)](#apidoc.element.eslint-plugin-angular.no_cookiestore.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.no_cookiestore.</span>meta

#### [module eslint-plugin-angular.no_directive_replace](#apidoc.module.eslint-plugin-angular.no_directive_replace)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.no_directive_replace.</span>create (context)](#apidoc.element.eslint-plugin-angular.no_directive_replace.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.no_directive_replace.</span>meta

#### [module eslint-plugin-angular.no_http_callback](#apidoc.module.eslint-plugin-angular.no_http_callback)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.no_http_callback.</span>create (context)](#apidoc.element.eslint-plugin-angular.no_http_callback.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.no_http_callback.</span>meta

#### [module eslint-plugin-angular.no_inline_template](#apidoc.module.eslint-plugin-angular.no_inline_template)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.no_inline_template.</span>create (context)](#apidoc.element.eslint-plugin-angular.no_inline_template.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.no_inline_template.</span>meta

#### [module eslint-plugin-angular.no_jquery_angularelement](#apidoc.module.eslint-plugin-angular.no_jquery_angularelement)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.no_jquery_angularelement.</span>create (context)](#apidoc.element.eslint-plugin-angular.no_jquery_angularelement.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.no_jquery_angularelement.</span>meta

#### [module eslint-plugin-angular.no_private_call](#apidoc.module.eslint-plugin-angular.no_private_call)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.no_private_call.</span>create (context)](#apidoc.element.eslint-plugin-angular.no_private_call.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.no_private_call.</span>meta

#### [module eslint-plugin-angular.no_run_logic](#apidoc.module.eslint-plugin-angular.no_run_logic)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.no_run_logic.</span>create (context)](#apidoc.element.eslint-plugin-angular.no_run_logic.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.no_run_logic.</span>meta

#### [module eslint-plugin-angular.no_service_method](#apidoc.module.eslint-plugin-angular.no_service_method)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.no_service_method.</span>create (context)](#apidoc.element.eslint-plugin-angular.no_service_method.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.no_service_method.</span>meta

#### [module eslint-plugin-angular.no_services](#apidoc.module.eslint-plugin-angular.no_services)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.no_services.</span>create (context)](#apidoc.element.eslint-plugin-angular.no_services.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.no_services.</span>meta

#### [module eslint-plugin-angular.on_destroy](#apidoc.module.eslint-plugin-angular.on_destroy)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.on_destroy.</span>create (context)](#apidoc.element.eslint-plugin-angular.on_destroy.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.on_destroy.</span>meta

#### [module eslint-plugin-angular.on_watch](#apidoc.module.eslint-plugin-angular.on_watch)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.on_watch.</span>create (context)](#apidoc.element.eslint-plugin-angular.on_watch.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.on_watch.</span>meta

#### [module eslint-plugin-angular.one_dependency_per_line](#apidoc.module.eslint-plugin-angular.one_dependency_per_line)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.one_dependency_per_line.</span>create (context)](#apidoc.element.eslint-plugin-angular.one_dependency_per_line.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.one_dependency_per_line.</span>meta

#### [module eslint-plugin-angular.prefer_component](#apidoc.module.eslint-plugin-angular.prefer_component)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.prefer_component.</span>create (context)](#apidoc.element.eslint-plugin-angular.prefer_component.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.prefer_component.</span>meta

#### [module eslint-plugin-angular.provider_name](#apidoc.module.eslint-plugin-angular.provider_name)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.provider_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.provider_name.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.provider_name.</span>meta

#### [module eslint-plugin-angular.rest_service](#apidoc.module.eslint-plugin-angular.rest_service)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.rest_service.</span>create (context)](#apidoc.element.eslint-plugin-angular.rest_service.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.rest_service.</span>meta

#### [module eslint-plugin-angular.service_name](#apidoc.module.eslint-plugin-angular.service_name)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.service_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.service_name.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.service_name.</span>meta

#### [module eslint-plugin-angular.timeout_service](#apidoc.module.eslint-plugin-angular.timeout_service)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.timeout_service.</span>create (context)](#apidoc.element.eslint-plugin-angular.timeout_service.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.timeout_service.</span>meta

#### [module eslint-plugin-angular.typecheck_array](#apidoc.module.eslint-plugin-angular.typecheck_array)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.typecheck_array.</span>create (context)](#apidoc.element.eslint-plugin-angular.typecheck_array.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.typecheck_array.</span>meta

#### [module eslint-plugin-angular.typecheck_date](#apidoc.module.eslint-plugin-angular.typecheck_date)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.typecheck_date.</span>create (context)](#apidoc.element.eslint-plugin-angular.typecheck_date.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.typecheck_date.</span>meta

#### [module eslint-plugin-angular.typecheck_function](#apidoc.module.eslint-plugin-angular.typecheck_function)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.typecheck_function.</span>create (context)](#apidoc.element.eslint-plugin-angular.typecheck_function.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.typecheck_function.</span>meta

#### [module eslint-plugin-angular.typecheck_number](#apidoc.module.eslint-plugin-angular.typecheck_number)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.typecheck_number.</span>create (context)](#apidoc.element.eslint-plugin-angular.typecheck_number.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.typecheck_number.</span>meta

#### [module eslint-plugin-angular.typecheck_object](#apidoc.module.eslint-plugin-angular.typecheck_object)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.typecheck_object.</span>create (context)](#apidoc.element.eslint-plugin-angular.typecheck_object.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.typecheck_object.</span>meta

#### [module eslint-plugin-angular.typecheck_string](#apidoc.module.eslint-plugin-angular.typecheck_string)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.typecheck_string.</span>create (context)](#apidoc.element.eslint-plugin-angular.typecheck_string.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.typecheck_string.</span>meta

#### [module eslint-plugin-angular.value_name](#apidoc.module.eslint-plugin-angular.value_name)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.value_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.value_name.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.value_name.</span>meta

#### [module eslint-plugin-angular.watchers_execution](#apidoc.module.eslint-plugin-angular.watchers_execution)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.watchers_execution.</span>create (context)](#apidoc.element.eslint-plugin-angular.watchers_execution.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.watchers_execution.</span>meta

#### [module eslint-plugin-angular.window_service](#apidoc.module.eslint-plugin-angular.window_service)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-angular.window_service.</span>create (context)](#apidoc.element.eslint-plugin-angular.window_service.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-angular.window_service.</span>meta



# <a name="apidoc.module.eslint-plugin-angular"></a>[module eslint-plugin-angular](#apidoc.module.eslint-plugin-angular)



# <a name="apidoc.module.eslint-plugin-angular.angularelement"></a>[module eslint-plugin-angular.angularelement](#apidoc.module.eslint-plugin-angular.angularelement)

#### <a name="apidoc.element.eslint-plugin-angular.angularelement.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.angularelement.</span>create (context)](#apidoc.element.eslint-plugin-angular.angularelement.create)
- description and source-code
```javascript
create = function (context) {
    return {
        CallExpression: function(node) {
            if (node.callee.name === '$' || node.callee.name === 'jQuery') {
                context.report(node, 'You should use angular.element instead of the jQuery $ object', {});
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.component_limit"></a>[module eslint-plugin-angular.component_limit](#apidoc.module.eslint-plugin-angular.component_limit)

#### <a name="apidoc.element.eslint-plugin-angular.component_limit.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.component_limit.</span>create (context)](#apidoc.element.eslint-plugin-angular.component_limit.create)
- description and source-code
```javascript
function wrapper(context) {
    reset();
    var ruleObject = ruleDefinition(context);
    injectCall(ruleObject, context, 'CallExpression:exit', checkCallee);
    injectCall(ruleObject, context, 'Program:exit', callAngularRules);
    return ruleObject;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.component_name"></a>[module eslint-plugin-angular.component_name](#apidoc.module.eslint-plugin-angular.component_name)

#### <a name="apidoc.element.eslint-plugin-angular.component_name.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.component_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.component_name.create)
- description and source-code
```javascript
create = function (context) {
    if (context.settings.angular === 2) {
        return {};
    }

    return {

        CallExpression: function(node) {
            var prefix = context.options[0];
            var convertedPrefix; // convert string from JSON .eslintrc to regex

            if (prefix === undefined) {
                return;
            }

            convertedPrefix = utils.convertPrefixToRegex(prefix);

            if (utils.isAngularComponentDeclaration(node)) {
                var name = node.arguments[0].value;

                if (name !== undefined && name.indexOf('ng') === 0) {
                    context.report(node, 'The {{component}} component should not start with "ng". This is reserved for AngularJS
 components', {
                        component: name
                    });
                } else if (name !== undefined && !convertedPrefix.test(name)) {
                    if (typeof prefix === 'string' && !utils.isStringRegexp(prefix)) {
                        context.report(node, 'The {{component}} component should be prefixed by {{prefix}}', {
                            component: name,
                            prefix: prefix
                        });
                    } else {
                        context.report(node, 'The {{component}} component should follow this pattern: {{prefix}}', {
                            component: name,
                            prefix: prefix.toString()
                        });
                    }
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.constant_name"></a>[module eslint-plugin-angular.constant_name](#apidoc.module.eslint-plugin-angular.constant_name)

#### <a name="apidoc.element.eslint-plugin-angular.constant_name.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.constant_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.constant_name.create)
- description and source-code
```javascript
create = function (context) {
    return {

        CallExpression: function(node) {
            var prefix = context.options[0];
            var convertedPrefix; // convert string from JSON .eslintrc to regex
            var isConstant;

            if (prefix === undefined) {
                return;
            }

            convertedPrefix = utils.convertPrefixToRegex(prefix);
            isConstant = utils.isAngularConstantDeclaration(node);

            if (isConstant) {
                var name = node.arguments[0].value;

                if (name !== undefined && name.indexOf('$') === 0) {
                    context.report(node, 'The {{constant}} constant should not start with "$". This is reserved for AngularJS services
', {
                        constant: name
                    });
                } else if (name !== undefined && !convertedPrefix.test(name)) {
                    if (typeof prefix === 'string' && !utils.isStringRegexp(prefix)) {
                        context.report(node, 'The {{constant}} constant should be prefixed by {{prefix}}', {
                            constant: name,
                            prefix: prefix
                        });
                    } else {
                        context.report(node, 'The {{constant}} constant should follow this pattern: {{prefix}}', {
                            constant: name,
                            prefix: prefix.toString()
                        });
                    }
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.controller_as"></a>[module eslint-plugin-angular.controller_as](#apidoc.module.eslint-plugin-angular.controller_as)

#### <a name="apidoc.element.eslint-plugin-angular.controller_as.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.controller_as.</span>create (context)](#apidoc.element.eslint-plugin-angular.controller_as.create)
- description and source-code
```javascript
create = function (context) {
    var badStatements = [];
    var controllerFunctions = [];

    // If your Angular code is written so that controller functions are in
    // separate files from your .controller() calls, you can specify a regex for your controller function names
    var controllerNameMatcher = context.options[0];
    if (controllerNameMatcher && utils.isStringRegexp(controllerNameMatcher)) {
        controllerNameMatcher = utils.convertStringToRegex(controllerNameMatcher);
    }

    // check node against known controller functions or pattern if specified
    function isControllerFunction(node) {
        return controllerFunctions.indexOf(node) >= 0 ||
            (controllerNameMatcher && (node.type === 'FunctionExpression' || node.type === 'FunctionDeclaration') &&
                node.id && controllerNameMatcher.test(node.id.name));
    }

    // for each of the bad uses, find any parent nodes that are controller functions
    function reportBadUses() {
        if (controllerFunctions.length > 0 || controllerNameMatcher) {
            badStatements.forEach(function(item) {
                item.parents.forEach(function(parent) {
                    if (isControllerFunction(parent)) {
                        context.report(item.stmt, 'You should not set properties on $scope in controllers. Use controllerAs syntax
 and add data to "this"');
                    }
                });
            });
        }
    }

    return {
        // Looking for .controller() calls here and getting the associated controller function
        'CallExpression:exit': function(node) {
            if (utils.isAngularControllerDeclaration(node)) {
                controllerFunctions.push(utils.getControllerDefinition(context, node));
            }
        },
        // statements are checked here for bad uses of $scope
        ExpressionStatement: function(stmt) {
            if (stmt.expression.type === 'AssignmentExpression' &&
                stmt.expression.left.object &&
                stmt.expression.left.object.name === '$scope' &&
                utils.scopeProperties.indexOf(stmt.expression.left.property.name) < 0) {
                badStatements.push({parents: context.getAncestors(), stmt: stmt});
            } else if (stmt.expression.type === 'CallExpression' &&
                stmt.expression.callee.object &&
                stmt.expression.callee.object.name === '$scope' &&
                utils.scopeProperties.indexOf(stmt.expression.callee.property.name) < 0) {
                badStatements.push({parents: context.getAncestors(), stmt: stmt});
            }
        },
        'Program:exit': function() {
            reportBadUses();
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.controller_as_route"></a>[module eslint-plugin-angular.controller_as_route](#apidoc.module.eslint-plugin-angular.controller_as_route)

#### <a name="apidoc.element.eslint-plugin-angular.controller_as_route.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.controller_as_route.</span>create (context)](#apidoc.element.eslint-plugin-angular.controller_as_route.create)
- description and source-code
```javascript
create = function (context) {
    return {
        CallExpression: function(node) {
            var routeObject = null;
            var stateObject = null;
            var hasControllerAs = false;
            var controllerProp = null;
            var stateName = null;

            if (utils.isRouteDefinition(node)) {
                // second argument in $routeProvider.when('route', {...})
                routeObject = node.arguments[1];

                if (routeObject.properties) {
                    routeObject.properties.forEach(function(prop) {
                        if (prop.key.name === 'controller') {
                            controllerProp = prop;

                            if (new RegExp('\\sas\\s').test(prop.value.value)) {
                                hasControllerAs = true;
                            }
                        }

                        if (prop.key.name === 'controllerAs') {
                            if (hasControllerAs) {
                                context.report(node, 'The controllerAs syntax is defined twice for the route "{{route}}"', {
                                    route: node.arguments[0].value
                                });
                            }

                            hasControllerAs = true;
                        }
                    });

                    // if it's a route without a controller, we shouldn't warn about controllerAs
                    if (controllerProp && !hasControllerAs) {
                        context.report(node, 'Route "{{route}}" should use controllerAs syntax', {
                            route: node.arguments[0].value
                        });
                    }
                }
            } else if (utils.isUIRouterStateDefinition(node)) {
                // state can be defined like .state({...}) or .state('name', {...})
                var isObjectState = node.arguments.length === 1;
                stateObject = isObjectState ? node.arguments[0] : node.arguments[1];

                if (stateObject && stateObject.properties) {
                    stateObject.properties.forEach(function(prop) {
                        if (prop.key.name === 'controller') {
                            controllerProp = prop;
                        }
                        if (prop.key.name === 'controllerAs') {
                            hasControllerAs = true;
                        }
                        // grab the name from the object for when they aren't using .state('name',...)
                        if (prop.key.name === 'name') {
                            stateName = prop.value.value;
                        }
                    });

                    if (!hasControllerAs && controllerProp) {
                        // if the controller is a string, controllerAs can be set like 'controller as vm'
                        if (controllerProp.value.type !== 'Literal' || controllerProp.value.value.indexOf(' as ') < 0) {
                            context.report(node, 'State "{{state}}" should use controllerAs syntax', {
                                state: isObjectState ? stateName : node.arguments[0].value
                            });
                        }
                    }
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.controller_as_vm"></a>[module eslint-plugin-angular.controller_as_vm](#apidoc.module.eslint-plugin-angular.controller_as_vm)

#### <a name="apidoc.element.eslint-plugin-angular.controller_as_vm.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.controller_as_vm.</span>create (context)](#apidoc.element.eslint-plugin-angular.controller_as_vm.create)
- description and source-code
```javascript
create = function (context) {
    var badStatements = [];
    var badCaptureStatements = [];
    var controllerFunctions = [];

    var viewModelName = context.options[0] || 'vm';
    // If your Angular code is written so that controller functions are in
    // separate files from your .controller() calls, you can specify a regex for your controller function names
    var controllerNameMatcher = context.options[1];
    if (controllerNameMatcher && utils.isStringRegexp(controllerNameMatcher)) {
        controllerNameMatcher = utils.convertStringToRegex(controllerNameMatcher);
    }

    // check node against known controller functions or pattern if specified
    function isControllerFunction(node) {
        return controllerFunctions.indexOf(node) >= 0 ||
            (controllerNameMatcher && (node.type === 'FunctionExpression' || node.type === 'FunctionDeclaration') &&
                node.id && controllerNameMatcher.test(node.id.name));
    }

    // for each of the bad uses, find any parent nodes that are controller functions
    function reportBadUses() {
        if (controllerFunctions.length > 0 || controllerNameMatcher) {
            badCaptureStatements.forEach(function(item) {
                item.parents.filter(isControllerFunction).forEach(function() {
                    context.report(item.stmt, 'You should assign "this" to a consistent variable across your project: {{capture}}',
                        {
                            capture: viewModelName
                        }
                    );
                });
            });
            badStatements.forEach(function(item) {
                item.parents.filter(isControllerFunction).forEach(function() {
                    context.report(item.stmt, 'You should not use "this" directly. Instead, assign it to a variable called "{{capture
}}"',
                        {
                            capture: viewModelName
                        }
                    );
                });
            });
        }
    }

    function isClassDeclaration(ancestors) {
        return ancestors.findIndex(function(ancestor) {
            return ancestor.type === 'ClassDeclaration';
        }) > -1;
    }

    return {
        // Looking for .controller() calls here and getting the associated controller function
        'CallExpression:exit': function(node) {
            if (utils.isAngularControllerDeclaration(node)) {
                controllerFunctions.push(utils.getControllerDefinition(context, node));
            }
        },
        // statements are checked here for bad uses of $scope
        ThisExpression: function(stmt) {
            var parents = context.getAncestors();
            if (!isClassDeclaration(parents)) {
                if (stmt.parent.type === 'VariableDeclarator') {
                    if (!stmt.parent.id || stmt.parent.id.name !== viewModelName) {
                        badCaptureStatements.push({parents: parents, stmt: stmt});
                    }
                } else {
                    badStatements.push({parents: parents, stmt: stmt});
                }
            }
        },
        'Program:exit': function() {
            reportBadUses();
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.controller_name"></a>[module eslint-plugin-angular.controller_name](#apidoc.module.eslint-plugin-angular.controller_name)

#### <a name="apidoc.element.eslint-plugin-angular.controller_name.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.controller_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.controller_name.create)
- description and source-code
```javascript
create = function (context) {
    return {

        CallExpression: function(node) {
            var prefix = context.options[0] || '/^[A-Z][a-zA-Z0-9]*Controller$/';
            var convertedPrefix; // convert string from JSON .eslintrc to regex

            convertedPrefix = utils.convertPrefixToRegex(prefix);

            var callee = node.callee;
            if (callee.type === 'MemberExpression' && callee.property.name === 'controller') {
<span class="apidocCodeCommentSpan">                /**
                 * Allow the usage of element.controller() and element.controller('directiveName') in unittests
                 */
</span>                if (node.arguments.length < 2) {
                    return;
                }

                var name = node.arguments[0].value;

                if (name !== undefined && !convertedPrefix.test(name)) {
                    if (typeof prefix === 'string' && !utils.isStringRegexp(prefix)) {
                        context.report(node, 'The {{controller}} controller should be prefixed by {{prefix}}', {
                            controller: name,
                            prefix: prefix
                        });
                    } else {
                        context.report(node, 'The {{controller}} controller should follow this pattern: {{prefix}}', {
                            controller: name,
                            prefix: prefix.toString()
                        });
                    }
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.deferred"></a>[module eslint-plugin-angular.deferred](#apidoc.module.eslint-plugin-angular.deferred)

#### <a name="apidoc.element.eslint-plugin-angular.deferred.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.deferred.</span>create (context)](#apidoc.element.eslint-plugin-angular.deferred.create)
- description and source-code
```javascript
create = function (context) {
    return {

        MemberExpression: function(node) {
            if (node.object.type === 'Identifier' && utils.isAngularServiceImport(node.object.name, '$q')) {
                if (node.property.type === 'Identifier' && node.property.name === 'defer') {
                    context.report(node, 'You should not create a new promise with this syntax. Use the $q(function(resolve, reject
) {}) syntax.', {});
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.definedundefined"></a>[module eslint-plugin-angular.definedundefined](#apidoc.module.eslint-plugin-angular.definedundefined)

#### <a name="apidoc.element.eslint-plugin-angular.definedundefined.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.definedundefined.</span>create (context)](#apidoc.element.eslint-plugin-angular.definedundefined.create)
- description and source-code
```javascript
create = function (context) {
    function isCompareOperator(operator) {
        return operator === '===' || operator === '!==' || operator === '==' || operator === '!=';
    }
    function reportError(node) {
        context.report(node, 'You should not use directly the "undefined" keyword. Prefer ' +
            'angular.isUndefined or angular.isDefined', {});
    }
<span class="apidocCodeCommentSpan">    /**
    *    Rule that check if we use angular.is(Un)defined() instead of the undefined keyword
    */
</span>    return {
        MemberExpression: function(node) {
            if (node.object.name === 'angular' &&
                node.parent !== undefined &&
                node.parent.parent !== undefined &&
                node.parent.parent.operator === '!') {
                if (node.property.name === 'isDefined') {
                    context.report(node, 'Instead of !angular.isDefined, you can use the out-of-box angular.isUndefined method', {});
                } else if (node.property.name === 'isUndefined') {
                    context.report(node, 'Instead of !angular.isUndefined, you can use the out-of-box angular.isDefined method', {});
                }
            }
        },
        BinaryExpression: function(node) {
            if (isCompareOperator(node.operator)) {
                if (utils.isTypeOfStatement(node.left) && node.right.value === 'undefined') {
                    reportError(node);
                } else if (utils.isTypeOfStatement(node.right) && node.left.value === 'undefined') {
                    reportError(node);
                } else if (node.left.type === 'Identifier' && node.left.name === 'undefined') {
                    reportError(node);
                } else if (node.right.type === 'Identifier' && node.right.name === 'undefined') {
                    reportError(node);
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.di"></a>[module eslint-plugin-angular.di](#apidoc.module.eslint-plugin-angular.di)

#### <a name="apidoc.element.eslint-plugin-angular.di.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.di.</span>create (context)](#apidoc.element.eslint-plugin-angular.di.create)
- description and source-code
```javascript
function wrapper(context) {
    reset();
    var ruleObject = ruleDefinition(context);
    injectCall(ruleObject, context, 'CallExpression:exit', checkCallee);
    injectCall(ruleObject, context, 'Program:exit', callAngularRules);
    return ruleObject;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.di_order"></a>[module eslint-plugin-angular.di_order](#apidoc.module.eslint-plugin-angular.di_order)

#### <a name="apidoc.element.eslint-plugin-angular.di_order.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.di_order.</span>create (context)](#apidoc.element.eslint-plugin-angular.di_order.create)
- description and source-code
```javascript
function wrapper(context) {
    reset();
    var ruleObject = ruleDefinition(context);
    injectCall(ruleObject, context, 'CallExpression:exit', checkCallee);
    injectCall(ruleObject, context, 'Program:exit', callAngularRules);
    return ruleObject;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.di_unused"></a>[module eslint-plugin-angular.di_unused](#apidoc.module.eslint-plugin-angular.di_unused)

#### <a name="apidoc.element.eslint-plugin-angular.di_unused.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.di_unused.</span>create (context)](#apidoc.element.eslint-plugin-angular.di_unused.create)
- description and source-code
```javascript
function wrapper(context) {
    reset();
    var ruleObject = ruleDefinition(context);
    injectCall(ruleObject, context, 'CallExpression:exit', checkCallee);
    injectCall(ruleObject, context, 'Program:exit', callAngularRules);
    return ruleObject;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.directive_name"></a>[module eslint-plugin-angular.directive_name](#apidoc.module.eslint-plugin-angular.directive_name)

#### <a name="apidoc.element.eslint-plugin-angular.directive_name.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.directive_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.directive_name.create)
- description and source-code
```javascript
create = function (context) {
    if (context.settings.angular === 2) {
        return {};
    }

    return {

        CallExpression: function(node) {
            var prefix = context.options[0];
            var convertedPrefix; // convert string from JSON .eslintrc to regex

            if (prefix === undefined) {
                return;
            }

            convertedPrefix = utils.convertPrefixToRegex(prefix);

            if (utils.isAngularDirectiveDeclaration(node)) {
                var name = node.arguments[0].value;

                if (name !== undefined && name.indexOf('ng') === 0) {
                    context.report(node, 'The {{directive}} directive should not start with "ng". This is reserved for AngularJS
 directives', {
                        directive: name
                    });
                } else if (name !== undefined && !convertedPrefix.test(name)) {
                    if (typeof prefix === 'string' && !utils.isStringRegexp(prefix)) {
                        context.report(node, 'The {{directive}} directive should be prefixed by {{prefix}}', {
                            directive: name,
                            prefix: prefix
                        });
                    } else {
                        context.report(node, 'The {{directive}} directive should follow this pattern: {{prefix}}', {
                            directive: name,
                            prefix: prefix.toString()
                        });
                    }
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.directive_restrict"></a>[module eslint-plugin-angular.directive_restrict](#apidoc.module.eslint-plugin-angular.directive_restrict)

#### <a name="apidoc.element.eslint-plugin-angular.directive_restrict.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.directive_restrict.</span>create (context)](#apidoc.element.eslint-plugin-angular.directive_restrict.create)
- description and source-code
```javascript
create = function (context) {
    var options = context.options[0] || {};
    var restrictOpt = options.restrict || 'AE';
    var explicitRestrict = options.explicit === 'always';
    var restrictChars = restrictOpt.split('');

    // Example RegExp for AE: /^A?E?$/
    var restrictRegExp = new RegExp('^' + restrictChars.join('?') + '?$');
    var foundDirectives = [];
    var checkedDirectives = [];
    var defaultRestrictions = ['AE', 'EA'];

    function checkLiteralNode(node) {
        if (node.type !== 'Literal') {
            return;
        }
        var directiveNode;
        context.getAncestors().some(function(ancestor) {
            if (utils.isAngularDirectiveDeclaration(ancestor)) {
                directiveNode = ancestor;
                return true;
            }
        });
        // The restrict property was not defined inside of a directive.
        if (!directiveNode) {
            return;
        }
        if (!explicitRestrict && defaultRestrictions.indexOf(node.value) !== -1) {
            context.report(node, 'No need to explicitly specify a default directive restriction');
            return;
        }

        if (!restrictRegExp.test(node.value)) {
            context.report(directiveNode, 'Disallowed directive restriction. It must be one of {{allowed}} in that order', {
                allowed: restrictOpt
            });
        }

        checkedDirectives.push(directiveNode);
    }

    return {
        CallExpression: function(node) {
            if (utils.isAngularDirectiveDeclaration(node)) {
                foundDirectives.push(node);
            }
        },
        AssignmentExpression: function(node) {
            // Only check for literal member property assignments.
            if (node.left.type !== 'MemberExpression') {
                return;
            }
            // Only check setting properties named 'restrict'.
            if (node.left.property.name !== 'restrict') {
                return;
            }
            checkLiteralNode(node.right);
        },
        Property: function(node) {
            // This only checks for objects which have defined a literal restrict property.
            if (node.key.name !== 'restrict') {
                return;
            }
            checkLiteralNode(node.value);
        },
        'Program:exit': function() {
            if (explicitRestrict) {
                foundDirectives.filter(function(directive) {
                    return checkedDirectives.indexOf(directive) < 0;
                }).forEach(function(directiveNode) {
                    context.report(directiveNode, 'Missing directive restriction');
                });
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.document_service"></a>[module eslint-plugin-angular.document_service](#apidoc.module.eslint-plugin-angular.document_service)

#### <a name="apidoc.element.eslint-plugin-angular.document_service.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.document_service.</span>create (context)](#apidoc.element.eslint-plugin-angular.document_service.create)
- description and source-code
```javascript
create = function (context) {
    return {
        MemberExpression: function(node) {
            if (node.object.name === 'document' || (node.object.name === 'window' && node.property.name === 'document')) {
                context.report(node, 'You should use the $document service instead of the default document object', {});
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.dumb_inject"></a>[module eslint-plugin-angular.dumb_inject](#apidoc.module.eslint-plugin-angular.dumb_inject)

#### <a name="apidoc.element.eslint-plugin-angular.dumb_inject.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.dumb_inject.</span>create (context)](#apidoc.element.eslint-plugin-angular.dumb_inject.create)
- description and source-code
```javascript
function wrapper(context) {
    reset();
    var ruleObject = ruleDefinition(context);
    injectCall(ruleObject, context, 'CallExpression:exit', checkCallee);
    injectCall(ruleObject, context, 'Program:exit', callAngularRules);
    return ruleObject;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.empty_controller"></a>[module eslint-plugin-angular.empty_controller](#apidoc.module.eslint-plugin-angular.empty_controller)

#### <a name="apidoc.element.eslint-plugin-angular.empty_controller.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.empty_controller.</span>create (context)](#apidoc.element.eslint-plugin-angular.empty_controller.create)
- description and source-code
```javascript
create = function (context) {
    function report(node, name) {
        context.report(node, 'The {{ctrl}} controller is useless because empty. You can remove it from your Router configuration
 or in one of your view', {
            ctrl: name
        });
    }

    return {

        CallExpression: function(node) {
            if (utils.isAngularControllerDeclaration(node)) {
                var name = node.arguments[0].value;

                var fn = node.arguments[1];
                if (utils.isArrayType(node.arguments[1])) {
                    fn = node.arguments[1].elements[node.arguments[1].elements.length - 1];
                }
                if (utils.isFunctionType(fn) && utils.isEmptyFunction(fn)) {
                    report(node, name);
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.factory_name"></a>[module eslint-plugin-angular.factory_name](#apidoc.module.eslint-plugin-angular.factory_name)

#### <a name="apidoc.element.eslint-plugin-angular.factory_name.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.factory_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.factory_name.create)
- description and source-code
```javascript
create = function (context) {
    return {

        CallExpression: function(node) {
            var prefix = context.options[0];
            var convertedPrefix; // convert string from JSON .eslintrc to regex
            var isFactory;

            if (prefix === undefined) {
                return;
            }

            convertedPrefix = utils.convertPrefixToRegex(prefix);
            isFactory = utils.isAngularFactoryDeclaration(node);

            if (isFactory) {
                var name = node.arguments[0].value;

                if (name !== undefined && name.indexOf('$') === 0) {
                    context.report(node, 'The {{factory}} factory should not start with "$". This is reserved for AngularJS services
', {
                        factory: name
                    });
                } else if (name !== undefined && !convertedPrefix.test(name)) {
                    if (typeof prefix === 'string' && !utils.isStringRegexp(prefix)) {
                        context.report(node, 'The {{factory}} factory should be prefixed by {{prefix}}', {
                            factory: name,
                            prefix: prefix
                        });
                    } else {
                        context.report(node, 'The {{factory}} factory should follow this pattern: {{prefix}}', {
                            factory: name,
                            prefix: prefix.toString()
                        });
                    }
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.file_name"></a>[module eslint-plugin-angular.file_name](#apidoc.module.eslint-plugin-angular.file_name)

#### <a name="apidoc.element.eslint-plugin-angular.file_name.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.file_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.file_name.create)
- description and source-code
```javascript
create = function (context) {
    var options = context.options[0] || {};
    var filename = path.basename(context.getFilename());
    var componentTypeMappings = createComponentTypeMappings(options);

    return {
        CallExpression: function(node) {
            if (utils.isAngularComponent(node) && utils.isMemberExpression(node.callee)) {
                var name = node.arguments[0].value;
                var type = componentTypeMappings[node.callee.property.name];
                var expectedName;

                if (type === undefined || (type === 'service' && node.callee.object.name === '$provide')) {
                    return;
                }

                if (!name) {
                    return;
                }
                expectedName = filenameUtil.createExpectedName(name, type, options);

                if (expectedName !== filename) {
                    context.report(node, 'Filename must be "{{expectedName}}"', {
                        expectedName: expectedName
                    });
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.filter_name"></a>[module eslint-plugin-angular.filter_name](#apidoc.module.eslint-plugin-angular.filter_name)

#### <a name="apidoc.element.eslint-plugin-angular.filter_name.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.filter_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.filter_name.create)
- description and source-code
```javascript
create = function (context) {
    return {

        CallExpression: function(node) {
            var prefix = context.options[0];
            var convertedPrefix; // convert string from JSON .eslintrc to regex;
            if (prefix === undefined) {
                return;
            }

            convertedPrefix = utils.convertPrefixToRegex(prefix);

            if (utils.isAngularFilterDeclaration(node)) {
                var name = node.arguments[0].value;

                if (name !== undefined && !convertedPrefix.test(name)) {
                    if (typeof prefix === 'string' && !utils.isStringRegexp(prefix)) {
                        context.report(node, 'The {{filter}} filter should be prefixed by {{prefix}}', {
                            filter: name,
                            prefix: prefix
                        });
                    } else {
                        context.report(node, 'The {{filter}} filter should follow this pattern: {{prefix}}', {
                            filter: name,
                            prefix: prefix.toString()
                        });
                    }
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.foreach"></a>[module eslint-plugin-angular.foreach](#apidoc.module.eslint-plugin-angular.foreach)

#### <a name="apidoc.element.eslint-plugin-angular.foreach.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.foreach.</span>create (context)](#apidoc.element.eslint-plugin-angular.foreach.create)
- description and source-code
```javascript
create = function (context) {
    return {
        MemberExpression: function(node) {
            if (node.object.type === 'Identifier' && node.object.name !== 'angular' && node.property.name === 'forEach') {
                context.report(node, 'You should use the angular.forEach method', {});
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.function_type"></a>[module eslint-plugin-angular.function_type](#apidoc.module.eslint-plugin-angular.function_type)

#### <a name="apidoc.element.eslint-plugin-angular.function_type.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.function_type.</span>create (context)](#apidoc.element.eslint-plugin-angular.function_type.create)
- description and source-code
```javascript
create = function (context) {
    var angularObjectList = ['animation', 'config', 'constant', 'controller', 'directive', 'factory', 'filter', 'provider', 'service
', 'value', 'decorator'];
    var configType = context.options[0] || 'anonymous';
    var messageByConfigType = {
        anonymous: 'Use anonymous functions instead of named function',
        named: 'Use named functions instead of anonymous function'
    };
    var message = messageByConfigType[configType];

    if (context.options[1]) {
        angularObjectList = context.options[1];
    }

    function checkType(arg) {
        return utils.isCallExpression(arg) ||
            (configType === 'named' && (utils.isIdentifierType(arg) || utils.isNamedInlineFunction(arg))) ||
            (configType === 'anonymous' && utils.isFunctionType(arg) && !utils.isNamedInlineFunction(arg));
    }

    return {

        CallExpression: function(node) {
            var callee = node.callee;
            var angularObjectName = callee.property && callee.property.name;
            var firstArgument = node.arguments[1];

            if (utils.isAngularComponent(node) && callee.type === 'MemberExpression' && angularObjectList.indexOf(angularObjectName
) >= 0) {
                if (checkType(firstArgument)) {
                    return;
                }

                if (utils.isArrayType(firstArgument)) {
                    var last = firstArgument.elements[firstArgument.elements.length - 1];
                    if (checkType(last) || (!utils.isFunctionType(last) && !utils.isIdentifierType(last))) {
                        return;
                    }
                }

                context.report(node, message, {});
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.interval_service"></a>[module eslint-plugin-angular.interval_service](#apidoc.module.eslint-plugin-angular.interval_service)

#### <a name="apidoc.element.eslint-plugin-angular.interval_service.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.interval_service.</span>create (context)](#apidoc.element.eslint-plugin-angular.interval_service.create)
- description and source-code
```javascript
create = function (context) {
    var message = 'You should use the $interval service instead of the default window.setInterval method';

    return {

        MemberExpression: function(node) {
            if (node.object.name === 'window' && node.property.name === 'setInterval') {
                context.report(node, message, {});
            }
        },

        CallExpression: function(node) {
            if (node.callee.name === 'setInterval') {
                context.report(node, message, {});
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.json_functions"></a>[module eslint-plugin-angular.json_functions](#apidoc.module.eslint-plugin-angular.json_functions)

#### <a name="apidoc.element.eslint-plugin-angular.json_functions.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.json_functions.</span>create (context)](#apidoc.element.eslint-plugin-angular.json_functions.create)
- description and source-code
```javascript
create = function (context) {
    return {

        MemberExpression: function(node) {
            if (node.object.name === 'JSON') {
                if (node.property.name === 'stringify') {
                    context.report(node, 'You should use the angular.toJson method instead of JSON.stringify', {});
                } else if (node.property.name === 'parse') {
                    context.report(node, 'You should use the angular.fromJson method instead of JSON.parse', {});
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.module_dependency_order"></a>[module eslint-plugin-angular.module_dependency_order](#apidoc.module.eslint-plugin-angular.module_dependency_order)

#### <a name="apidoc.element.eslint-plugin-angular.module_dependency_order.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.module_dependency_order.</span>create (context)](#apidoc.element.eslint-plugin-angular.module_dependency_order.create)
- description and source-code
```javascript
create = function (context) {
    var options = context.options[0] || {};
    var groupedMode = options.grouped !== false;
    var moduleRegex;
    if (groupedMode) {
        moduleRegex = utils.convertPrefixToRegex(options.prefix);
    }

    var standard = [
        // Libraries in the angular.js repository
        'ng',
        'ngAnimate',
        'ngAria',
        'ngCookies',
        'ngLocale',
        'ngMessageFormat',
        'ngMessages',
        'ngMock',
        'ngResource',
        'ngRoute',
        'ngSanitize',
        'ngTouch',

        // Libraries maintained by the angular team, but in another repository
        'ngMaterial',
        'ngNewRouter'
    ];

    function checkLiteral(node) {
        if (node && node.type !== 'Literal' && node.type !== 'Identifier') {
            context.report(node, 'Unexpected non-literal or identifier value' + node.type);
            return false;
        }
        if (!node) {
            return false;
        }
        return true;
    }

    function checkCombined(deps) {
        var lastCorrect;
        deps.elements.forEach(function(node) {
            if (!checkLiteral(node)) {
                return;
            }
            var value = node.value || node.name;
            if (lastCorrect === undefined || lastCorrect.localeCompare(value) < 0) {
                lastCorrect = value;
            } else {
                context.report(node, '{{current}} should be sorted before {{last}}', {
                    current: value,
                    last: lastCorrect
                });
            }
        });
    }

    function isStandardModule(value) {
        return standard.indexOf(value) !== -1;
    }

    function isCustomModule(value) {
        return moduleRegex && moduleRegex.test(value);
    }

    function checkGrouped(deps) {
        var lastCorrect;
        var group = 'standard';
        deps.elements.forEach(function loop(node) {
            if (!checkLiteral(node)) {
                return;
            }
            var value = node.value || node.name;
            if (lastCorrect === undefined) {
                lastCorrect = value;
                if (isCustomModule(value)) {
                    group = 'custom';
                } else if (standard.indexOf(value) === -1) {
                    group = 'third party';
                }
                return;
            }
            if (group === 'standard') {
                if (isStandardModule(value)) {
                    if (lastCorrect.localeCompare(value) > 0) {
                        context.report(node, '{{current}} should be sorted before {{last}}', {
                            current: value,
                            last: lastCorrect
                        });
                    } else {
                        lastCorrect = value;
                    }
                } else {
                    if (isCustomModule(value)) {
                        group = 'custom';
                    } else {
                        group = 'third party';
                    }
                    lastCorrect = value;
                }
            }
            if (group === 'third party') {
                if (isStandardModule(value)) {
                    context.report(node, '{{current}} is a standard module and should be sorted before {{last}}', {
                        current: value,
                        last: lastCorrect
                    });
                } else if (isCustomModule(value)) {
                    group = 'custom';
                    lastCorrect = value;
                } else if (lastCorrect.localeCompare(value) > 0) {
                    context.report(node, '{{current}} should be sorted before {{last}}', {
                        current: value,
                        last: lastCorrect
                    });
                } else {
                    lastCorrect = value;
                }
            }
            if (group === 'custom') {
                if (isStandardModule(value)) {
                    context.report(node, '{{current}} is a standard module and sho ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.module_getter"></a>[module eslint-plugin-angular.module_getter](#apidoc.module.eslint-plugin-angular.module_getter)

#### <a name="apidoc.element.eslint-plugin-angular.module_getter.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.module_getter.</span>create (context)](#apidoc.element.eslint-plugin-angular.module_getter.create)
- description and source-code
```javascript
create = function (context) {
    return {

        ExpressionStatement: function(node) {
            if ((utils.isAngularControllerDeclaration(node.expression) ||
                utils.isAngularFilterDeclaration(node.expression) ||
                utils.isAngularServiceDeclaration(node.expression) ||
                utils.isAngularFactoryDeclaration(node.expression) ||
                utils.isAngularConstantDeclaration(node.expression) ||
                utils.isAngularValueDeclaration(node.expression) ||
                utils.isAngularDirectiveDeclaration(node.expression) ||
                utils.isAngularRunSection(node.expression) ||
                utils.isAngularConfigSection(node.expression)) &&

                !utils.isAngularModuleDeclaration(node.expression)) {
                var calleeObject = node.expression.callee.object;

                while (calleeObject !== undefined && calleeObject.type === 'CallExpression' && !utils.isAngularModuleGetter(calleeObject
)) {
                    calleeObject = calleeObject.callee.object;
                }
                if (!(calleeObject !== undefined && calleeObject.type === 'CallExpression' && utils.isAngularModuleGetter(calleeObject
))) {
                    context.report(node, 'Avoid using a variable and instead use chaining with the getter syntax.');
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.module_name"></a>[module eslint-plugin-angular.module_name](#apidoc.module.eslint-plugin-angular.module_name)

#### <a name="apidoc.element.eslint-plugin-angular.module_name.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.module_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.module_name.create)
- description and source-code
```javascript
create = function (context) {
    return {

        CallExpression: function(node) {
            var prefix = context.options[0];
            var convertedPrefix; // convert string from JSON .eslintrc to regex

            if (prefix === undefined) {
                return;
            }

            convertedPrefix = utils.convertPrefixToRegex(prefix);

            if (utils.isAngularModuleDeclaration(node)) {
                var name = node.arguments[0].value;

                if (name !== undefined && name.indexOf('ng') === 0) {
                    context.report(node, 'The {{module}} module should not start with "ng". This is reserved for AngularJS modules
', {
                        module: name
                    });
                } else if (name !== undefined && !convertedPrefix.test(name)) {
                    if (typeof prefix === 'string' && !utils.isStringRegexp(prefix)) {
                        context.report(node, 'The {{module}} module should be prefixed by {{prefix}}', {
                            module: name,
                            prefix: prefix
                        });
                    } else {
                        context.report(node, 'The {{module}} module should follow this pattern: {{prefix}}', {
                            module: name,
                            prefix: prefix.toString()
                        });
                    }
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.module_setter"></a>[module eslint-plugin-angular.module_setter](#apidoc.module.eslint-plugin-angular.module_setter)

#### <a name="apidoc.element.eslint-plugin-angular.module_setter.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.module_setter.</span>create (context)](#apidoc.element.eslint-plugin-angular.module_setter.create)
- description and source-code
```javascript
create = function (context) {
    return {

        VariableDeclaration: function(node) {
            var variableDeclarator = node.declarations[0];
            var rightExpression;

            if (variableDeclarator.init) {
                rightExpression = variableDeclarator.init;

                if (rightExpression.arguments && utils.isAngularModuleDeclaration(rightExpression)) {
                    context.report(rightExpression, 'Declare modules without a variable using the setter syntax.');
                }
            }
        },
        AssignmentExpression: function(node) {
            if (node.right.arguments && utils.isAngularModuleDeclaration(node.right)) {
                context.report(node.right, 'Declare modules without a variable using the setter syntax.');
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.no_controller"></a>[module eslint-plugin-angular.no_controller](#apidoc.module.eslint-plugin-angular.no_controller)

#### <a name="apidoc.element.eslint-plugin-angular.no_controller.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.no_controller.</span>create (context)](#apidoc.element.eslint-plugin-angular.no_controller.create)
- description and source-code
```javascript
create = function (context) {
    return {

        CallExpression: function(node) {
            if (utils.isAngularControllerDeclaration(node)) {
                context.report(node, 'Based on the Component-First Pattern, you should avoid the use of controllers', {});
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.no_cookiestore"></a>[module eslint-plugin-angular.no_cookiestore](#apidoc.module.eslint-plugin-angular.no_cookiestore)

#### <a name="apidoc.element.eslint-plugin-angular.no_cookiestore.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.no_cookiestore.</span>create (context)](#apidoc.element.eslint-plugin-angular.no_cookiestore.create)
- description and source-code
```javascript
create = function (context) {
    return {

        MemberExpression: function(node) {
            if (node.object && node.object.name === '$cookieStore') {
                context.report(node, 'Since Angular 1.4, the $cookieStore service is deprecated. Please use now the $cookies service
.', {});
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.no_directive_replace"></a>[module eslint-plugin-angular.no_directive_replace](#apidoc.module.eslint-plugin-angular.no_directive_replace)

#### <a name="apidoc.element.eslint-plugin-angular.no_directive_replace.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.no_directive_replace.</span>create (context)](#apidoc.element.eslint-plugin-angular.no_directive_replace.create)
- description and source-code
```javascript
function wrapper(context) {
    reset();
    var ruleObject = ruleDefinition(context);
    injectCall(ruleObject, context, 'CallExpression:exit', checkCallee);
    injectCall(ruleObject, context, 'Program:exit', callAngularRules);
    return ruleObject;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.no_http_callback"></a>[module eslint-plugin-angular.no_http_callback](#apidoc.module.eslint-plugin-angular.no_http_callback)

#### <a name="apidoc.element.eslint-plugin-angular.no_http_callback.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.no_http_callback.</span>create (context)](#apidoc.element.eslint-plugin-angular.no_http_callback.create)
- description and source-code
```javascript
create = function (context) {
    var httpMethods = [
        'delete',
        'get',
        'head',
        'jsonp',
        'patch',
        'post',
        'put'
    ];

    function isHttpCall(node) {
        if (node.callee.type === 'MemberExpression') {
            return httpMethods.indexOf(node.callee.property.name) !== -1 ||
                (node.callee.object.type === 'CallExpression' && isHttpCall(node.callee.object));
        }
        if (node.callee.type === 'Identifier') {
            return node.callee.name === '$http';
        }
    }

    return {
        CallExpression: function(node) {
            if (node.callee.type !== 'MemberExpression') {
                return;
            }
            if (node.callee.property.name === 'success' && isHttpCall(node)) {
                return context.report(node, '$http success is deprecated. Use then instead');
            }
            if (node.callee.property.name === 'error' && isHttpCall(node)) {
                context.report(node, '$http error is deprecated. Use then or catch instead');
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.no_inline_template"></a>[module eslint-plugin-angular.no_inline_template](#apidoc.module.eslint-plugin-angular.no_inline_template)

#### <a name="apidoc.element.eslint-plugin-angular.no_inline_template.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.no_inline_template.</span>create (context)](#apidoc.element.eslint-plugin-angular.no_inline_template.create)
- description and source-code
```javascript
create = function (context) {
    // Extracts any HTML tags.
    var regularTagPattern = /<(.+?)>/g;
    // Extracts self closing HTML tags.
    var selfClosingTagPattern = /<(.+?)\/>/g;

    var allowSimple = (context.options[0] && context.options[0].allowSimple) !== false;

    function reportComplex(node) {
        context.report(node, 'Inline template is too complex. Use an external template instead');
    }

    return {
        Property: function(node) {
            if (node.key.name !== 'template' || node.value.type !== 'Literal') {
                return;
            }
            if (!allowSimple) {
                context.report(node, 'Inline templates are not allowed. Use an external template instead');
            }
            if ((node.value.value && node.value.value.match(regularTagPattern) || []).length > 2) {
                return reportComplex(node);
            }
            if ((node.value.value && node.value.value.match(selfClosingTagPattern) || []).length > 1) {
                return reportComplex(node);
            }
            if (node.value && node.value.raw.indexOf('\\') !== -1) {
                reportComplex(node);
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.no_jquery_angularelement"></a>[module eslint-plugin-angular.no_jquery_angularelement](#apidoc.module.eslint-plugin-angular.no_jquery_angularelement)

#### <a name="apidoc.element.eslint-plugin-angular.no_jquery_angularelement.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.no_jquery_angularelement.</span>create (context)](#apidoc.element.eslint-plugin-angular.no_jquery_angularelement.create)
- description and source-code
```javascript
create = function (context) {
    return {

        MemberExpression: function(node) {
            if (node.object.name === 'angular' && node.property.name === 'element') {
                if (node.parent !== undefined && node.parent.parent !== undefined &&
                    node.parent.parent.type === 'CallExpression' &&
                    node.parent.parent.callee.type === 'Identifier' &&
                    (node.parent.parent.callee.name === 'jQuery' || node.parent.parent.callee.name === '$')) {
                    context.report(node, 'angular.element returns already a jQLite element. No need to wrap with the jQuery object
', {});
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.no_private_call"></a>[module eslint-plugin-angular.no_private_call](#apidoc.module.eslint-plugin-angular.no_private_call)

#### <a name="apidoc.element.eslint-plugin-angular.no_private_call.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.no_private_call.</span>create (context)](#apidoc.element.eslint-plugin-angular.no_private_call.create)
- description and source-code
```javascript
create = function (context) {
    var options = context.options[0] || {};
    var allowed = options.allow || [];

    function check(node, name) {
        if (name.slice(0, 2) === '$$' && allowed.indexOf(name) < 0) {
            context.report(node, 'Using $$-prefixed Angular objects/methods are not recommended', {});
        }
    }
    return {

        Identifier: function(node) {
            check(node, node.name);
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.no_run_logic"></a>[module eslint-plugin-angular.no_run_logic](#apidoc.module.eslint-plugin-angular.no_run_logic)

#### <a name="apidoc.element.eslint-plugin-angular.no_run_logic.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.no_run_logic.</span>create (context)](#apidoc.element.eslint-plugin-angular.no_run_logic.create)
- description and source-code
```javascript
function wrapper(context) {
    reset();
    var ruleObject = ruleDefinition(context);
    injectCall(ruleObject, context, 'CallExpression:exit', checkCallee);
    injectCall(ruleObject, context, 'Program:exit', callAngularRules);
    return ruleObject;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.no_service_method"></a>[module eslint-plugin-angular.no_service_method](#apidoc.module.eslint-plugin-angular.no_service_method)

#### <a name="apidoc.element.eslint-plugin-angular.no_service_method.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.no_service_method.</span>create (context)](#apidoc.element.eslint-plugin-angular.no_service_method.create)
- description and source-code
```javascript
create = function (context) {
    return {

        CallExpression: function(node) {
            if (utils.isAngularComponent(node) && node.callee.property && node.callee.property.name === 'service') {
                context.report(node, 'You should prefer the factory() method instead of service()', {});
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.no_services"></a>[module eslint-plugin-angular.no_services](#apidoc.module.eslint-plugin-angular.no_services)

#### <a name="apidoc.element.eslint-plugin-angular.no_services.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.no_services.</span>create (context)](#apidoc.element.eslint-plugin-angular.no_services.create)
- description and source-code
```javascript
create = function (context) {
    let angularObjectList = ['controller', 'filter', 'directive'];
    let badServices = [];
    let map;
    let message = 'REST API calls should be implemented in a specific service';

    function isArray(item) {
        return Object.prototype.toString.call(item) === '[object Array]';
    }

    function isObject(item) {
        return Object.prototype.toString.call(item) === '[object Object]';
    }

    if (context.options[0] === undefined) {
        badServices = [/\$http/, /\$resource/, /Restangular/, /\$q/, /\$filter/];
    }

    if (isArray(context.options[0])) {
        badServices = context.options[0];
    }

    if (isArray(context.options[1])) {
        angularObjectList = context.options[1];
    }

    if (isObject(context.options[0])) {
        map = context.options[0];

        let result = [];
        let prop;

        for (prop in map) {
            if (map.hasOwnProperty(prop)) {
                result.push(prop);
            }
        }

        angularObjectList = result;
    }

    function isSetBedService(serviceName, angularObjectName) {
        if (map) {
            return map[angularObjectName].find(object => utils.convertPrefixToRegex(object).test(serviceName));
        }
        return badServices.find(object => utils.convertPrefixToRegex(object).test(serviceName));
    }

    return {

        CallExpression: function(node) {
            let callee = node.callee;

            if (utils.isAngularComponent(node) && callee.type === 'MemberExpression' && angularObjectList.indexOf(callee.property
.name) >= 0) {
                if (utils.isFunctionType(node.arguments[1])) {
                    node.arguments[1].params.forEach(function(service) {
                        if (service.type === 'Identifier' && isSetBedService(service.name, callee.property.name)) {
                            context.report(node, message + ' (' + service.name + ' in ' + callee.property.name + ')', {});
                        }
                    });
                }

                if (utils.isArrayType(node.arguments[1])) {
                    node.arguments[1].elements.forEach(function(service) {
                        if (service.type === 'Literal' && isSetBedService(service.value, callee.property.name)) {
                            context.report(node, message + ' (' + service.value + ' in ' + callee.property.name + ')', {});
                        }
                    });
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.on_destroy"></a>[module eslint-plugin-angular.on_destroy](#apidoc.module.eslint-plugin-angular.on_destroy)

#### <a name="apidoc.element.eslint-plugin-angular.on_destroy.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.on_destroy.</span>create (context)](#apidoc.element.eslint-plugin-angular.on_destroy.create)
- description and source-code
```javascript
create = function (context) {
    function report(node) {
        context.report(node, 'You probably misspelled $on("$destroy").');
    }

<span class="apidocCodeCommentSpan">    /**
     * Return true if the given node is a call expression calling a function
     * named '$on'.
     */
</span>    function isOn(node) {
        var calledFunction = node.callee;
        if (calledFunction.type !== 'MemberExpression') {
            return false;
        }

        // can only easily tell what name was used if a simple
        // identifiers were used to access it.
        var accessedFunction = calledFunction.property;
        if (accessedFunction.type !== 'Identifier') {
            return false;
        }

        var functionName = accessedFunction.name;

        return functionName === '$on';
    }

    /**
     * Return true if the given node is a call expression that has a first
     * argument of the string '$destroy'.
     */
    function isFirstArgDestroy(node) {
        var args = node.arguments;

        return (args.length >= 1 &&
            args[0].type === 'Literal' &&
            args[0].value === 'destroy');
    }

    return {
        CallExpression: function(node) {
            if (isOn(node) && isFirstArgDestroy(node)) {
                report(node);
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.on_watch"></a>[module eslint-plugin-angular.on_watch](#apidoc.module.eslint-plugin-angular.on_watch)

#### <a name="apidoc.element.eslint-plugin-angular.on_watch.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.on_watch.</span>create (context)](#apidoc.element.eslint-plugin-angular.on_watch.create)
- description and source-code
```javascript
create = function (context) {
    function report(node, method) {
        context.report(node, 'The "{{method}}" call should be assigned to a variable, in order to be destroyed during the $destroy
 event', {
            method: method
        });
    }

<span class="apidocCodeCommentSpan">    /**
     * Return true if the given node is a call expression calling a function
     * named '$on' or '$watch' on an object named '$scope', '$rootScope' or
     * 'scope'.
     */
</span>    function isScopeOnOrWatch(node, scopes) {
        if (node.type !== 'CallExpression') {
            return false;
        }

        var calledFunction = node.callee;
        if (calledFunction.type !== 'MemberExpression') {
            return false;
        }

        // can only easily tell what name was used if a simple
        // identifiers were used to access it.
        var parentObject = calledFunction.object;
        var accessedFunction = calledFunction.property;

        // cannot check name of the parent object if it is returned from a
        // complex expression.
        if (parentObject.type !== 'Identifier' ||
            accessedFunction.type !== 'Identifier') {
            return false;
        }

        var objectName = parentObject.name;
        var functionName = accessedFunction.name;

        return scopes.indexOf(objectName) >= 0 && (functionName === '$on' ||
            functionName === '$watch');
    }

    /**
     * Return true if the given node is a call expression that has a first
     * argument of the string '$destroy'.
     */
    function isFirstArgDestroy(node) {
        var args = node.arguments;

        return (args.length >= 1 &&
            args[0].type === 'Literal' &&
            args[0].value === '$destroy');
    }

    return {

        CallExpression: function(node) {
            if (isScopeOnOrWatch(node, ['$rootScope']) && !isFirstArgDestroy(node)) {
                if (node.parent.type !== 'VariableDeclarator' &&
                    node.parent.type !== 'AssignmentExpression' &&
                    !(isScopeOnOrWatch(node.parent, ['$rootScope', '$scope', 'scope']) &&
                        isFirstArgDestroy(node.parent))) {
                    report(node, node.callee.property.name);
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.one_dependency_per_line"></a>[module eslint-plugin-angular.one_dependency_per_line](#apidoc.module.eslint-plugin-angular.one_dependency_per_line)

#### <a name="apidoc.element.eslint-plugin-angular.one_dependency_per_line.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.one_dependency_per_line.</span>create (context)](#apidoc.element.eslint-plugin-angular.one_dependency_per_line.create)
- description and source-code
```javascript
create = function (context) {
    var angularObjectList = ['animation', 'config', 'constant', 'controller', 'directive', 'factory', 'filter', 'provider', 'service
', 'value', 'decorator'];

    function checkArgumentPositionInFunction(node) {
        if (!node.params || node.params.length < 2) {
            return;
        }

        var linesFound = [];
        node.params.forEach(reportMultipleItemsInOneLine.bind(null, node, linesFound));
    }

    function reportMultipleItemsInOneLine(node, linesFound, item) {
        var currentLine = item.loc.start.line;
        if (linesFound.indexOf(currentLine) !== -1) {
            context.report({
                node: node,
                message: 'Do not use multiple dependencies in one line',
                loc: item.loc.start
            });
        }
        linesFound.push(currentLine);
    }

    function checkArgumentPositionArrayExpression(angularComponentNode, arrayNode) {
        var linesFound = [];

        arrayNode.elements.forEach(function(element) {
            if (element.type === 'Literal') {
                reportMultipleItemsInOneLine(arrayNode, linesFound, element);
            }
            if (element.type === 'FunctionExpression') {
                checkArgumentPositionInFunction(element);
            }
            if (element.type === 'Identifier') {
                var fn = getFunctionDeclaration(angularComponentNode, element.name);
                checkArgumentPositionInFunction(fn);
            }
        });
    }

    function findFunctionDeclarationByDeclaration(body, fName) {
        return body.find(function(item) {
            return item.type === 'FunctionDeclaration' && item.id.name === fName;
        });
    }

    function findFunctionDeclarationByVariableDeclaration(body, fName) {
        var fn;
        body.forEach(function(item) {
            if (fn) {
                return;
            }
            if (item.type === 'VariableDeclaration') {
                item.declarations.forEach(function(declaration) {
                    if (declaration.type === 'VariableDeclarator' &&
                        declaration.id &&
                        declaration.id.name === fName &&
                        declaration.init &&
                        declaration.init.type === 'FunctionExpression'
                    ) {
                        fn = declaration.init;
                    }
                });
            }
        });
        return fn;
    }

    function getFunctionDeclaration(node, fName) {
        if (node.type === 'BlockStatement' || node.type === 'Program') {
            if (node.body) {
                var fn = findFunctionDeclarationByDeclaration(node.body, fName);
                if (fn) {
                    return fn;
                }
                fn = findFunctionDeclarationByVariableDeclaration(node.body, fName);
                if (fn) {
                    return fn;
                }
            }
        }
        if (node.parent) {
            return getFunctionDeclaration(node.parent, fName);
        }
    }

    return {

        CallExpression: function(node) {
            var fn;
            if (utils.isAngularComponent(node) &&
                node.callee.type === 'MemberExpression' &&
                node.arguments[1].type === 'FunctionExpression' &&
                angularObjectList.indexOf(node.callee.property.name) >= 0) {
                fn = node.arguments[1];
                return checkArgumentPositionInFunction(fn);
            }
            if (utils.isAngularComponent(node) &&
                node.callee.type === 'MemberExpression' &&
                node.arguments[1].type === 'Identifier' &&
                angularObjectList.indexOf(node.callee.property.name) >= 0) {
                var fName = node.arguments[1].name;
                fn = getFunctionDeclaration(node, fName);
                if (fn) {
                    return checkArgumentPositionInFunction(fn);
                }
            }
            if (utils.isAngularComponent(node) &&
                node.callee.type === 'MemberExpression' & ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.prefer_component"></a>[module eslint-plugin-angular.prefer_component](#apidoc.module.eslint-plugin-angular.prefer_component)

#### <a name="apidoc.element.eslint-plugin-angular.prefer_component.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.prefer_component.</span>create (context)](#apidoc.element.eslint-plugin-angular.prefer_component.create)
- description and source-code
```javascript
function wrapper(context) {
    reset();
    var ruleObject = ruleDefinition(context);
    injectCall(ruleObject, context, 'CallExpression:exit', checkCallee);
    injectCall(ruleObject, context, 'Program:exit', callAngularRules);
    return ruleObject;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.provider_name"></a>[module eslint-plugin-angular.provider_name](#apidoc.module.eslint-plugin-angular.provider_name)

#### <a name="apidoc.element.eslint-plugin-angular.provider_name.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.provider_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.provider_name.create)
- description and source-code
```javascript
create = function (context) {
    return {

        CallExpression: function(node) {
            var prefix = context.options[0];
            var convertedPrefix; // convert string from JSON .eslintrc to regex
            var isProvider;

            if (prefix === undefined) {
                return;
            }

            convertedPrefix = utils.convertPrefixToRegex(prefix);
            isProvider = utils.isAngularProviderDeclaration(node);

            if (isProvider) {
                var name = node.arguments[0].value;

                if (name !== undefined && name.indexOf('$') === 0) {
                    context.report(node, 'The {{provider}} provider should not start with "$". This is reserved for AngularJS services
', {
                        provider: name
                    });
                } else if (name !== undefined && !convertedPrefix.test(name)) {
                    if (typeof prefix === 'string' && !utils.isStringRegexp(prefix)) {
                        context.report(node, 'The {{provider}} provider should be prefixed by {{prefix}}', {
                            provider: name,
                            prefix: prefix
                        });
                    } else {
                        context.report(node, 'The {{provider}} provider should follow this pattern: {{prefix}}', {
                            provider: name,
                            prefix: prefix.toString()
                        });
                    }
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.rest_service"></a>[module eslint-plugin-angular.rest_service](#apidoc.module.eslint-plugin-angular.rest_service)

#### <a name="apidoc.element.eslint-plugin-angular.rest_service.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.rest_service.</span>create (context)](#apidoc.element.eslint-plugin-angular.rest_service.create)
- description and source-code
```javascript
create = function (context) {
    var angularObjectList = ['controller', 'filter', 'directive', 'service', 'factory', 'provider'];
    var services = ['$http', '$resource', 'Restangular'];
    var message = 'You should use the same service ({{method}}) for REST API calls';


    return {

        CallExpression: function(node) {
            function checkElement(element) {
                if (element.type === 'Identifier' && services.indexOf(element.name) >= 0 && context.options[0] !== element.name) {
                    context.report(node, message, {
                        method: context.options[0]
                    });
                } else if (element.type === 'Literal' && services.indexOf(element.value) >= 0 && context.options[0] !== element.
value) {
                    context.report(node, message, {
                        method: context.options[0]
                    });
                }
            }

            function checkAllElements(elements) {
                elements.forEach(checkElement);
            }

            var callee = node.callee;

            if (utils.isAngularComponent(node) && callee.type === 'MemberExpression' && angularObjectList.indexOf(callee.property
.name) >= 0) {
                if (utils.isFunctionType(node.arguments[1])) {
                    checkAllElements(node.arguments[1].params);
                }

                if (utils.isArrayType(node.arguments[1])) {
                    checkAllElements(node.arguments[1].elements);
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.service_name"></a>[module eslint-plugin-angular.service_name](#apidoc.module.eslint-plugin-angular.service_name)

#### <a name="apidoc.element.eslint-plugin-angular.service_name.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.service_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.service_name.create)
- description and source-code
```javascript
create = function (context) {
    warnForDeprecatedBehavior(context.options);

    return {

        CallExpression: function(node) {
            var config = getConfig(context.options);
            var prefix = getPrefixFromOptions(context.options);
            var convertedPrefix; // convert string from JSON .eslintrc to regex
            var isService;

            if (prefix === undefined) {
                return;
            }

            convertedPrefix = utils.convertPrefixToRegex(prefix);

            if (config.oldBehavior) {
                isService = utils.isAngularServiceDeclarationDeprecated(node);
            } else {
                isService = utils.isAngularServiceDeclaration(node);
            }

            if (isService) {
                var name = node.arguments[0].value;

                if (name !== undefined && name.indexOf('$') === 0) {
                    context.report(node, 'The {{service}} service should not start with "$". This is reserved for AngularJS services
', {
                        service: name
                    });
                } else if (name !== undefined && !convertedPrefix.test(name)) {
                    if (typeof prefix === 'string' && !utils.isStringRegexp(prefix)) {
                        context.report(node, 'The {{service}} service should be prefixed by {{prefix}}', {
                            service: name,
                            prefix: prefix
                        });
                    } else {
                        context.report(node, 'The {{service}} service should follow this pattern: {{prefix}}', {
                            service: name,
                            prefix: prefix.toString()
                        });
                    }
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.timeout_service"></a>[module eslint-plugin-angular.timeout_service](#apidoc.module.eslint-plugin-angular.timeout_service)

#### <a name="apidoc.element.eslint-plugin-angular.timeout_service.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.timeout_service.</span>create (context)](#apidoc.element.eslint-plugin-angular.timeout_service.create)
- description and source-code
```javascript
create = function (context) {
    var message = 'You should use the $timeout service instead of the default window.setTimeout method';

    return {

        MemberExpression: function(node) {
            if (node.property.name !== 'setTimeout') {
                return;
            }

            if (node.object.type === 'Identifier') {
                if ((node.object.name === 'window' || node.object.name === '$window')) {
                    context.report(node, message, {});
                }

                return;
            }

            // Detect expression this.$window.setTimeout which is what we would see in ES6 code when using classes
            var parentNode = node.object;

            if (parentNode.object.type === 'ThisExpression' && parentNode.property.name === '$window') {
                context.report(node, message, {});
            }
        },

        CallExpression: function(node) {
            if (node.callee.name === 'setTimeout') {
                context.report(node, message, {});
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.typecheck_array"></a>[module eslint-plugin-angular.typecheck_array](#apidoc.module.eslint-plugin-angular.typecheck_array)

#### <a name="apidoc.element.eslint-plugin-angular.typecheck_array.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.typecheck_array.</span>create (context)](#apidoc.element.eslint-plugin-angular.typecheck_array.create)
- description and source-code
```javascript
create = function (context) {
    function recordError(node, origin) {
        if (node.type === 'Literal' && node.value === '[object Array]') {
            context.report(origin, 'You should use the angular.isArray method', {});
        }
    }

    return {
        MemberExpression: function(node) {
            if (node.object.name === 'Array' && node.property.name === 'isArray') {
                context.report(node, 'You should use the angular.isArray method', {});
            }
        },
        BinaryExpression: function(node) {
            if (node.operator === '===' || node.operator === '!==') {
                if (utils.isTypeOfStatement(node.left) || utils.isToStringStatement(node.left)) {
                    recordError(node.right, node);
                } else if (utils.isTypeOfStatement(node.right) || utils.isToStringStatement(node.right)) {
                    recordError(node.left, node);
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.typecheck_date"></a>[module eslint-plugin-angular.typecheck_date](#apidoc.module.eslint-plugin-angular.typecheck_date)

#### <a name="apidoc.element.eslint-plugin-angular.typecheck_date.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.typecheck_date.</span>create (context)](#apidoc.element.eslint-plugin-angular.typecheck_date.create)
- description and source-code
```javascript
create = function (context) {
    function recordError(node, origin) {
        if (node.type === 'Literal' && node.value === '[object Date]') {
            context.report(origin, 'You should use the angular.isDate method', {});
        }
    }

    return {

        BinaryExpression: function(node) {
            if (node.operator === '===' || node.operator === '!==') {
                if (utils.isTypeOfStatement(node.left) || utils.isToStringStatement(node.left)) {
                    recordError(node.right, node);
                } else if (utils.isTypeOfStatement(node.right) || utils.isToStringStatement(node.right)) {
                    recordError(node.left, node);
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.typecheck_function"></a>[module eslint-plugin-angular.typecheck_function](#apidoc.module.eslint-plugin-angular.typecheck_function)

#### <a name="apidoc.element.eslint-plugin-angular.typecheck_function.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.typecheck_function.</span>create (context)](#apidoc.element.eslint-plugin-angular.typecheck_function.create)
- description and source-code
```javascript
create = function (context) {
    function recordError(node, origin) {
        if (node.type === 'Literal' && (node.value === 'function' || node.value === '[object Function]')) {
            context.report(origin, 'You should use the angular.isFunction method', {});
        }
    }

    return {

        BinaryExpression: function(node) {
            if (node.operator === '===' || node.operator === '!==') {
                if (utils.isTypeOfStatement(node.left) || utils.isToStringStatement(node.left)) {
                    recordError(node.right, node);
                } else if (utils.isTypeOfStatement(node.right) || utils.isToStringStatement(node.right)) {
                    recordError(node.left, node);
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.typecheck_number"></a>[module eslint-plugin-angular.typecheck_number](#apidoc.module.eslint-plugin-angular.typecheck_number)

#### <a name="apidoc.element.eslint-plugin-angular.typecheck_number.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.typecheck_number.</span>create (context)](#apidoc.element.eslint-plugin-angular.typecheck_number.create)
- description and source-code
```javascript
create = function (context) {
    function recordError(node, origin) {
        if (node.type === 'Literal' && (node.value === 'number' || node.value === '[object Number]')) {
            context.report(origin, 'You should use the angular.isNumber method', {});
        }
    }


    return {

        BinaryExpression: function(node) {
            if (node.operator === '===' || node.operator === '!==') {
                if (utils.isTypeOfStatement(node.left) || utils.isToStringStatement(node.left)) {
                    recordError(node.right, node);
                } else if (utils.isTypeOfStatement(node.right) || utils.isToStringStatement(node.right)) {
                    recordError(node.left, node);
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.typecheck_object"></a>[module eslint-plugin-angular.typecheck_object](#apidoc.module.eslint-plugin-angular.typecheck_object)

#### <a name="apidoc.element.eslint-plugin-angular.typecheck_object.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.typecheck_object.</span>create (context)](#apidoc.element.eslint-plugin-angular.typecheck_object.create)
- description and source-code
```javascript
create = function (context) {
    function recordError(node, origin) {
        if (node.type === 'Literal' && (node.value === 'object' || node.value === '[object Object]')) {
            context.report(origin, 'You should use the angular.isObject method', {});
        }
    }

    return {
        BinaryExpression: function(node) {
            if (node.operator === '===' || node.operator === '!==') {
                if (utils.isTypeOfStatement(node.left) || utils.isToStringStatement(node.left)) {
                    recordError(node.right, node);
                } else if (utils.isTypeOfStatement(node.right) || utils.isToStringStatement(node.right)) {
                    recordError(node.left, node);
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.typecheck_string"></a>[module eslint-plugin-angular.typecheck_string](#apidoc.module.eslint-plugin-angular.typecheck_string)

#### <a name="apidoc.element.eslint-plugin-angular.typecheck_string.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.typecheck_string.</span>create (context)](#apidoc.element.eslint-plugin-angular.typecheck_string.create)
- description and source-code
```javascript
create = function (context) {
    function recordError(node, origin) {
        if (node.type === 'Literal' && (node.value === 'string' || node.value === '[object String]')) {
            context.report(origin, 'You should use the angular.isString method', {});
        }
    }

    return {

        BinaryExpression: function(node) {
            if (node.operator === '===' || node.operator === '!==') {
                if (utils.isTypeOfStatement(node.left) || utils.isToStringStatement(node.left)) {
                    recordError(node.right, node);
                } else if (utils.isTypeOfStatement(node.right) || utils.isToStringStatement(node.right)) {
                    recordError(node.left, node);
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.value_name"></a>[module eslint-plugin-angular.value_name](#apidoc.module.eslint-plugin-angular.value_name)

#### <a name="apidoc.element.eslint-plugin-angular.value_name.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.value_name.</span>create (context)](#apidoc.element.eslint-plugin-angular.value_name.create)
- description and source-code
```javascript
create = function (context) {
    return {

        CallExpression: function(node) {
            var prefix = context.options[0];
            var convertedPrefix; // convert string from JSON .eslintrc to regex
            var isValue;

            if (prefix === undefined) {
                return;
            }

            convertedPrefix = utils.convertPrefixToRegex(prefix);
            isValue = utils.isAngularValueDeclaration(node);

            if (isValue) {
                var name = node.arguments[0].value;

                if (name !== undefined && name.indexOf('$') === 0) {
                    context.report(node, 'The {{value}} value should not start with "$". This is reserved for AngularJS services
', {
                        value: name
                    });
                } else if (name !== undefined && !convertedPrefix.test(name)) {
                    if (typeof prefix === 'string' && !utils.isStringRegexp(prefix)) {
                        context.report(node, 'The {{value}} value should be prefixed by {{prefix}}', {
                            value: name,
                            prefix: prefix
                        });
                    } else {
                        context.report(node, 'The {{value}} value should follow this pattern: {{prefix}}', {
                            value: name,
                            prefix: prefix.toString()
                        });
                    }
                }
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.watchers_execution"></a>[module eslint-plugin-angular.watchers_execution](#apidoc.module.eslint-plugin-angular.watchers_execution)

#### <a name="apidoc.element.eslint-plugin-angular.watchers_execution.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.watchers_execution.</span>create (context)](#apidoc.element.eslint-plugin-angular.watchers_execution.create)
- description and source-code
```javascript
create = function (context) {
    var method = context.options[0] || '$digest';
    var methods = ['$apply', '$digest'];
    return {

        MemberExpression: function(node) {
            var forbiddenMethod = methods.filter(function(m) {
                return m !== method;
            });
            if (forbiddenMethod.length > 0 && node.property.type === 'Identifier' && forbiddenMethod.indexOf(node.property.name) >=
0) {
                context.report(node, 'Instead of using the {{forbidden}}() method, you should prefer {{method}}()', {
                    forbidden: node.property.name,
                    method: method
                });
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-angular.window_service"></a>[module eslint-plugin-angular.window_service](#apidoc.module.eslint-plugin-angular.window_service)

#### <a name="apidoc.element.eslint-plugin-angular.window_service.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-angular.window_service.</span>create (context)](#apidoc.element.eslint-plugin-angular.window_service.create)
- description and source-code
```javascript
create = function (context) {
    var restrict = ['document', 'setInterval', 'setTimeout'];
    return {

        MemberExpression: function(node) {
            if (node.object.name === 'window' && restrict.indexOf(node.property.name) < 0) {
                context.report(node, 'You should use the $window service instead of the default window object', {});
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
