## 声明位置

  声明必须位于HTML文档顶端首行,位于<html>标签之前.
  
## 声明作用

  <!DOCTYPE>声明不是标签,他是指示浏览器(web)关于页面使用的哪个HTML版本以进行渲染的指令.
  若不指定文件类型,即不声明,HTML不合法,且大部分浏览器会使用怪异模式来渲染页面,这意味着浏览器认为你自己也不知道究竟要做什么,并按浏览器自己的方法处理代码.
  
## 浏览器渲染模式模式

  (1)标准模式(strict mode):以HTML与Css标准对文档进行解析与处理.
  (2)怪异模式(quirks mode):浏览器以自己的方式渲染文档,即模拟老旧处理器以兼容可能存在的大量老旧网页.
  
## 常见DOCTYPE声明

  ### HTML 5  :
    <!DOCTYPE html>
  ### HTML 4.01 Strict :
    该 DTD 包含所有 HTML 元素和属性，但不包括展示性的和弃用的元素（比如 font）。不允许框架集（Framesets）。
    <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
  ### HTML 4.01 Transitional
    该 DTD 包含所有 HTML 元素和属性，包括展示性的和弃用的元素（比如 font）。不允许框架集（Framesets）。
    <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" 
    "http://www.w3.org/TR/html4/loose.dtd">
  ### HTML 4.01 Frameset
    该 DTD 等同于 HTML 4.01 Transitional，但允许框架集内容。
    <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN" 
    "http://www.w3.org/TR/html4/frameset.dtd">
  ### XHTML 1.0 Strict
    该 DTD 包含所有 HTML 元素和属性，但不包括展示性的和弃用的元素（比如 font）。不允许框架集（Framesets）。必须以格式正确的 XML 来编写标记。
    <!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" 
    "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
  ### XHTML 1.0 Transitional
    该 DTD 包含所有 HTML 元素和属性，包括展示性的和弃用的元素（比如 font）。不允许框架集（Framesets）。必须以格式正确的 XML 来编写标记。
    <!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "
    http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
  ### XHTML 1.0 Frameset
    该 DTD 等同于 XHTML 1.0 Transitional，但允许框架集内容。
    <!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Frameset//EN" 
    "http://www.w3.org/TR/xhtml1/DTD/xhtml1-frameset.dtd">
  ### XHTML 1.1
    该 DTD 等同于 XHTML 1.0 Strict，但允许添加模型（例如提供对东亚语系的 ruby 支持）。
    <!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN" "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
    
