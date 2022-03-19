## I simulated an orbital solar system to scale!

**Project description:** Equipped with some knowledge on physics, I used actual coordinates of the planets and the Sun with the velocity and calculated the gravitational influence subjected to each celestial bodies. The final result gives out accurate orbital periods, semimajor/ semiminor lengths and I can input the output coordinates to get a simulation in VMD! This is what I learnt and used from this project.

### 1. Lots and lots of arrays and matrices

If you have two planets together, they would have the same gravitational force (although the "force" can look different on them). If you have a bunch of them, each would have their own gravitational pair with one another! You are able to keep track of it using a matrix.

```python
for i in range(N):
        for j in range(N):
            #Gets the force numerator
            if i!=j:      
                force[i,j] = -G*p_list[i].mass*p_list[j].mass/(sep[i,j])**3 * sep_vector[i,j]
                
            else:
                continue```

### 2. Long term scale meant better integration time

```python
if (isAwesome){
  return true
}
```

### 3. Support the selection of appropriate statistical tools and techniques

<img src="images/dummy_thumbnail.jpg?raw=true"/>

### 4. Provide a basis for further data collection through surveys or experiments

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
