
但是，在调用时**String.Format**方法，不需要能够专注于你想要调用的特定重载。 相反，您可以调用与方法[复合格式字符串](~/docs/standard/base-types/composite-formatting.md)包括一个或多个格式项。 分配每个格式项的数字的索引;第一个索引从 0 开始。 除了初始的字符串，方法调用都应具有任意多个其他参数，因为它具有索引值。 例如，一个字符串，其格式项的索引为 0 和 1 应具有 2 的自变量;其中一个具有索引 0 到 5 之间应该有 6 自变量。 您的语言编译器将然后解析到的特定重载方法调用**String.Format**方法。   
 
使用的文档的更多详细**String.Format**方法，请参阅[String.Format 方法入门](#Starting)和[请勿调用的方法？](#FTaskList)。    