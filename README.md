# dynamic_proxy
动态代理的两种方式：
  <ul>
  <li>jdk自带的动态代理：</li>
    只能代理实现了接口的类，实现InvocationHandler接口的invoke()方法。
  
  <li>cglib包动态代理：</li>
    针对类实现代理，原理是通过目标类生成一个子类，并覆盖方法实现增强，通过实现MethodInterceptor接口，getInstance()方法用于生成一个子类，intercept()方法进行拦截。
  </ul>
