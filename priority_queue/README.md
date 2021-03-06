# STLite-Priority_queue

## 实现细节

最终提交仅需要提交 `priority_queue.hpp` 的内容。

你需要完成的内容：

+ 构造函数（两种）
+ 析构函数
+ 赋值重载
+ 获得队首元素 `top`
+ 元素入队 `push`
+ 队首元素出队 `pop`
+ 队列大小 `size`
+ 判断队列是否为空 `empty`
+ 队列合并 `merge`

具体细节可以查看下发的`priority_queue.hpp`框架。

注意：

- 你能使用的头文件仅限于下发框架中提供的头文件。
- `merge` 复杂度不能超过 $O(\log n)$，这意味着你可能需要写可并堆。
- 有测试内存泄漏的数据点。

## 分数构成

正常情况下，在 OJ 上通过测试数据可以获得 80% 的分数，CR 占 20% 的分数。

如果在CR时，发现有任何违规行为（包括但不限于使用其它头文件、使用非常规方法通过测试点以及`merge`复杂度超过 $O(\log n)$），你最终的得分都有可能为 $0$ 分。

## 截止日期

3月19日（第五周周六）23:00 前。

