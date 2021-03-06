# 1.5.2 (2021-03-17)


### Features

* **uncategorized:** add `NgContent` snippet



# 1.5.1 (2021-03-10)


### Bug Fixes

* **common-directives:** `NgIfElse` snippet - fix `elseBlock` tabstop
numbering



# 1.5.0 (2021-03-10)


### Features

* **common-directives:** add the end of line tabstops
* **forms-directives:** add the end of line tabstops; key-value tabstop
for `NgModelOptions`
* **router-directives:** add the end of line tabstops; key-value
tabstops for the following snippets: `QueryParams`, `State`



# 1.4.1 (2021-03-08)


### Chore

* **README:** remove unnecessary Angular version statement



# 1.4.0 (2021-03-08)


### Features

* **uncategorized:** add support for the following bindings: `attr`,
`style`, `innerHTML` and `hidden`. Move `class` binding from
`common-directives` to `uncategorized`, because it is not in a common
module



# 1.3.0 (2021-03-08)


### Features

* **common-directives:** add additional choices in some of the prefixes
to enhance the matching process
* **forms-directives:** add additional choices in some of the prefixes
to enhance the matching process and additional objects of some of the
snippets, for dynamic expression property binding
* **router-directives:** add additional choices in some of the prefixes
to enhance the matching process and additional objects of some of the
snippets, for dynamic expression property binding

### Improvements

* **README**: add a screenshot of an example usage
* **package.json:** add keywords; replace `displayName` with more
enhanced specificity



# 1.1.0 (2021-03-07)


### Features

* **pipes:** add support for pipes
* **events:** add support for events

### Improvements

* **snippets' file:** remove `snippets.json` and instead add following
JSON files in new `snippets` directory: `common-directives`,
`forms-directives`, `router-directives`, `structural-directives`,
`pipes`, `events`. This way it will be easier to organize stuff