# kudp.go TODO
kudp implemented by golang

# udp可靠传输 --- kudp

## **目标**
基于udp协议实现可靠传输，为更上层应用层提供可靠的"传输层"！

## **几个说明**

1. 基于udp协议
2. 实现可靠的传输
3. 封装过程不保持长连接
4. 基于数据报而不是字节流
5. 不做拥塞控制，只要设法保证数据不错、不丢、不乱

## [**kudp.js**](https://github.com/skybosi/kudp)
由于一定的历史原因，kudp的第一个实现版本是js编写，将在kudp.js 实现第一个版本后，直接翻译为golang实现

## [kudp protocol](https://github.com/skybosi/kudp/blob/master/doc/kudp.md)
