What is TDD?
1. [red] Write a failing test ->2.
2. [green] write code to pass the test -> 3.
3. refactor -> 1.

//Arrange 

//Act

//Assert
* Assert.NotNUll(result);
* Assert.Equal(a,b);

![](images/TDD-1.png)


refactor code : create a constructor to initialize 

    public class RequestProcesorTests{
        private RequestProcessor _processor;

        public RequestProcesorTests(){
            _processor = new RequestProcessor();
        }

    }