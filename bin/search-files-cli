#!/usr/bin/env node
const fs = require('fs')
const { join } = require('path')

const fileName = process.argv.splice(2, process.argv.length -1).join()

function searchFiles(filter, startPath = '.') {
    const files = fs.readdirSync(startPath)

    files.map(filePath => {
        const fullFilePath = join(startPath, filePath);
        const statFilePath = fs.lstatSync(fullFilePath);
    
        if (statFilePath.isDirectory()) {
            return searchFiles(filter, fullFilePath)
        }

        if (fullFilePath.indexOf(filter) !== -1) {
            console.log(fullFilePath)
        }
    })
}

searchFiles(fileName)