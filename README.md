# check-repeat-http-url
检查url是否重复
使用方法

const CheckRepeatHttpUrl = require("check-repeat-http-url");

new RequireRepeatHttpUrl({
  folderPath: path.resolve(__dirname, 'src'), // 要检查的文件夹位置
  extensions: ".js", // 解析的文件类型，可选值".js"或者".ts"或者[".js", ".ts"]
})