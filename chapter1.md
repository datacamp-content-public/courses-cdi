---
title: 'Chapter Title Here'
description: 'Chapter description goes here.'
---

## Example coding exercise

```yaml
type: NormalExercise
key: e8c1edbe67
lang: python
xp: 100
skills: 2
```

This is an example exercise.

`@instructions`
Add a `test3` attribute to the test step.

`@hint`


`@pre_exercise_code`
```{python}
import yaml
workflow_file = ""
```

`@sample_code`
```{python}
workflow_file = """
test: 'a'
  test2: 'b'
"""

wf = yaml.load(workflow_file)

```

`@solution`
```{python}
workflow_file = """
test: 'a'
  test2: 'b'
  test3: 'c'
"""
```

`@sct`
```{python}
Ex().check_object('wf').check_keys('test')
```

---

## Insert exercise title here

```yaml
type: VideoExercise
key: 640fa48abb
xp: 50
```

`@projector_key`
cbdb217a4dbfb1fb7142e7e7dac13b19

---

## Insert exercise title here

```yaml
type: NormalExercise
key: a17b318efb
xp: 100
```

<!-- Guidelines for contexts: https://instructor-support.datacamp.com/en/articles/2375526-course-coding-exercises. -->

`@instructions`
<!-- Guidelines for instructions https://instructor-support.datacamp.com/en/articles/2375526-course-coding-exercises. -->
- Instruction 1
- Instruction 2

`@hint`
<!-- Examples of good hints: https://instructor-support.datacamp.com/en/articles/2379164-hints-best-practices. -->
- This is an example hint.
- This is an example hint.

`@pre_exercise_code`
```{python}
# test:
#   test2:
```

`@sample_code`
```{python}

```

`@solution`
```{python}
# test:
#   test2: A
```

`@sct`
```{python}
# Examples of good success messages: https://instructor-support.datacamp.com/en/articles/2299773-exercise-success-messages.
```
