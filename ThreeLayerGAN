import keras as k


class firstnerualnetwork(k.Sequential):
    def __init__(self,y_train,x_train):
        self.add(k.Dense(64, input_dim=8, activation='relu'))
        self.add(k.Dense(32, activation='relu'))
        self.add(k.Dense(1, activation='sigmoid'))

        
        self.compile(optimizer='adam', loss='binary_crossentropy', metrics=['accuracy'])


        self.fit(secondnerualnetwork.lmao, self.y_train, epochs=10, batch_size=32)
class secondnerualnetwork(k.Sequential):
    def __init__(self,y_train,x_train):
        self.add(k.Dense(64, input_dim=8, activation='relu'))
        self.add(k.Dense(32, activation='relu'))
        self.add(k.Dense(1, activation='sigmoid'))
        
        self.compile(optimizer='adam', loss='binary_crossentropy', metrics=['accuracy'])

        lmao = self.fit(thirdnerualnetwork.v, self.y_train, epochs=10, batch_size=32)
        
class thirdnerualnetwork(k.Sequential):
    def __init__(self,y_train,x_train):
        self.add(k.Dense(64, input_dim=8, activation='relu'))
        self.add(k.Dense(32, activation='relu'))
        self.add(k.Dense(1, activation='sigmoid'))
        self.compile(optimizer='adam', loss='binary_crossentropy', metrics=['accuracy'])

        v = self.fit(k.X_train, k.y_train, epochs=10, batch_size=32)
