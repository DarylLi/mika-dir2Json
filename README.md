# mika-dir2Json

make dir files and path struct to a formatted object json file

how to use it:
//generateMainKey: 生成目录名称
//entryFilePath: ./导入目录相对路径
//outputFileName: 导出文件名

cargo run ${generateMainKey} ${entryFilePath} ${outputFileName}
ex:cargo run rust-umi-generate ./src/react-umi ./src/outputJson.js
