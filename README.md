
arrayList-tree
================

A small library that converts Array of list to tree

## Installation

  `npm install arraylist-to-tree`

## Usage

    const tree = require('arraylistTotree');

  var list = [
    {
        id: 1,
        parentInt: 0
    }, {
        id: 2,
        parentInt: 1
    }, {
        id: 3,
        parentInt: 1
    }, {
        id: 4,
        parentInt: 2
    }, {
        id: 5,
        parentInt: 2
    }];

## Result
[{
    "id": 1,
    "parentInt": 0,
    "children": [
        {
            "id": 2,
            "parentInt": 1,
            "children": [
                {
                    "id": 4,
                    "parentInt": 2
                }, {
                    "id": 5,
                    "parentInt": 2
                }
            ]
        }]
    }]

## Tests

  `npm test`

## Keywords

	nodejs
	typescript 
	javascript
	list-to-tree 
	arraylist 
	treeview 
	convertToTree
	javascript collection to treejs
	collection to treecollectionjquery 
	list to treejquery 
	collection to tree
