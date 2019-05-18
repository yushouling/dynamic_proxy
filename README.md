# dynamic_proxy
动态代理的两种方式：
  <ul>
  <li>jdk自带的动态代理：只能代理实现了接口的类，通过实现InvocationHandler接口的invoke()方法</li>
  
  <li>cglib包动态代理：针对类实现代理，继承目标类生成一个子类，并覆盖方法实现增强，通过实现MethodInterceptor接口intercept()方法</li>
  </ul>
