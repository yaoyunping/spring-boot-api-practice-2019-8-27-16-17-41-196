Spring:是分层的Java SE/EE应用full-stack轻量级的开源框架，可以通过对JavaEE API进行封装，使API的使用难度大大降低。
SpringBoot：对Spring的缺点进行改善和优化，是Spring的基础上进行封装，提供了一种快速使用Spring的方式，使开发人员不必在配置与逻辑业务之间进行思维切换，全身心投入到逻辑业务的代码编写中，提高开发效率。
Bean:是Spring框架下的核心容器，包含大量管理类的实例。
@RestController:声明这是一个控制器，要处理一些请求。
@RequestMapping：是一个映射，说明要调用哪个地方的资源。
@RequestParam：请求入参，url中的?后面参数可以用
@RequestBody：将前端传递过来的数据注入到参数中以供使用，Json字符串部分可以用
@GetMapping:将HTTP Get请求映射到特定处理程序的方法
@PostMapping:将HTTP Post请求映射到特定处理程序的方法
@PutMapping:将HTTP Put请求映射到特定处理程序的方法
@DeleteMapping:将HTTP Delete请求映射到特定处理程序的方法
@PathVariable：调取变量入参。
@AutoWrie：从Spring框架中注入被注解标志过的可被找到的资源。
@Service：用于是标记实现类，是把spring容器中的bean进行实例化，也就是等同于new操作。
