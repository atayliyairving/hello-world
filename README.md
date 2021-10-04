# hello-world
just another repository
I am Atayliya Irving, I am in the group the amigos and I am the database team leader
from __future__ import print_function

%tensorflow_version 1.x
import tensorflow as tf
try:
  tf.contrib.eager.enable_eager_execution()
except ValueError:
  pass  # enable_eager_execution errors after its first call

tensor = tf.constant('Hello, world!')
tensor_value = tensor.numpy()
print(tensor_value.decode())
