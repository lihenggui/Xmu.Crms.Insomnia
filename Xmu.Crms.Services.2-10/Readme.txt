SeminarGroupService：
前半部分由许驹雄完成，QQ：980753915
后半部分由孙仲玄完成，QQ：1731744887

TopicService：
由汪亚东完成，QQ：994094745

注：SeminarGroupService中的AutomaticallyGrouping方法由于需要使用使用其他小组的service方法，故没有测试。
除此之外，所有service的方法均经过数据库测试，在使用中如果遇到问题请联系上述人员解决。

v2：注释掉了SeminarGroupService里的AutomaticallyGrouping方法，此方法由于引入了其他service类，会出现服务器内部错误。
更新了部分方法。与标准组同步。

为了不出现奇怪的错误，建议将ITopicService，ISeminarGroupService,两个文件替换成此压缩文件里的。
models里的topic.cs有点小瑕疵，建议用本压缩文件里的topic.cs的替换掉