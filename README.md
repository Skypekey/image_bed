# image_bed_on_gitee

所有在线文档所使用图片均位于此库中。

## 目录说明

- conf：存储在线图片以及证明图片相关的信息。
    - free_images.json：证明图片相关信息。包含如下内容：

        ```json
        "无版权图片网站名": {
            "源文件名": [
                "使用图片转化后的图片路径",
                "使用图片在线路径",
                "使用图片原在线路径",
                "证明图片转化后的图片路径",
                "证明图片在线路径"
            ]
        ```

    - images.json：在线图片相关信息。包含如下内容：

        ```json
        "在线图片文件名": [
            "转化后的图片路径",
            "在线路径"
        ]
        ```

- free_image_proof：所使用的无版权图片的证明。以无版权图片网站名目录包含年份目录，年份目录包含月份目录的目录格式存储。
- free_image_no_proof：来源未知的网络图片，可能存在版权问题。不在线使用，仅本地使用，此处用于备份。
- images：在线图片路径。以年份目录包含月份目录的目录格式存储。
- Waring.png：用于本地提示。