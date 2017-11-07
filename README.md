# nginx_image_filter_module_bmp_support
让nginx image_filter module支持bmp格式图片

该文件是在nginx 1.4.7版本的基础上修改的，位置：nginx-1.4.7/src/http/modules/

需要依赖libgd，libgb版本要>2.0，否则不支持bmp格式的图片渲染，会报错：error: implicit declaration of function ‘gdImageCreateFromBmpPtr’

