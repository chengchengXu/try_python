
## SignalType
* **Type** `int32LE`
* **Value Meaning**
    - **`0`** 无状态
    - **`1`** 未跟踪 | 弃用
    - **`2`** 限时跟踪
    - **`3`** 持续跟踪
    - **`4`** 未公开 | 弃用
    - **`5`** 限时公开
    - **`6`** 持续公开

## MessageType
* **Type** `int32LE`
* **Value Meaning**
    - **`1`** 邀请加入 | xxx邀请你加入他/她的圈子
    - **`2`** 邀请者邀请成功 | xxx邀请你加入他/她的圈子
    - **`3`** 邀请者邀请失败 | xxx邀请你加入他/她的圈子
    - **`4`** 被邀请者邀请成功 | 同意了你的入圈邀请
    - **`5`** 被邀请者邀请失败 | 拒绝了你的入圈邀请
    - **`6`** 请求加入 | xxx申请加入你的圈子
    - **`7`** 请求者请求成功 | xxx申请加入你的圈子
    - **`8`** 请求者请求失败 | xxx申请加入你的圈子
    - **`9`** 被请求者请求成功 | 同意了你的入圈申请
    - **`10`** 被请求者请求失败 | 拒绝了你的入圈申请
    - **`11`** 退出圈子 | xxx退出了你的圈子
    - **`12`** 请出圈子 | xxx将你移出他/她的圈子

## ReadFlag
* **Type** `int32LE`
* **Value Meaning**
    - **`0`** 未读
    - **`1`** 已读

## IS_UserUserRelation_e
* **Type** `int32LE`
* **Value Meaning**
    - **`0`** 无关系
    - **`1`** A在B圈子
    - **`2`** B在A圈子
    - **`3`** 互在圈子

## IS_UserAccountRelation_e
* **Type** `int32LE`
* **Value Meaning**
    - **`0`** 无关系
    - **`1`** 用户关注账户
    - **`2`** 用户跟踪账户
