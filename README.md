# lightrpc
��������rpc  
�ͻ���ʹ��
```
		Client.connect("127.0.0.1", 6161);
		ITest proxy = ProxyInterface.getProxy(ITest.class);
```
�����ʹ��
```
		ITest test= new TestImpl();	
		Invoker.put(test);

		Server.bind(6161);
```
û�м��ɿ�ܣ�������Ҫ�ֶ�ע�ᵽInvoker