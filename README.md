Conceptual Breakdown:
      I chose to work on the titanic notebook. I chose this one since it sounded more interesting, personally. The model is a random forest ensemble performing binary classification on whether or not passengers survived the shipwreck. Off the bat, I am seeing that this data may be quite complex, and the max_depth param on the model is set to 3. I have not done extensive work with these models, but I suspect that is a little too 'shallow' to fully capture some patterns we may find. Furthermore, I think that the title someone holds would most likely play into their survivability, as bleak as that is, so it would be worth looking into adding that feature into the model. Another one to look into is the sibsp and parch features, this is the number of siblings or spouses that the passenger has on board and the number of parents / children the passenger has respectively; if this number is higher, most likely the survivability is also higher.
Current Gameplan:
     1. Add a feature tracking people's title / People's family count (Implement family count feature first.)

     2. Increase the max_depth of the trees

     I will see if adding the extra feature gets me past the threshold before I increase the max_depth. I feel that would be the most efficient option
