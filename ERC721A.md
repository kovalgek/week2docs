### ERC721A
#### How does ERC721A save gas?
ERC721A saves gas by reducing duplicate storage
and updates owner data once per batch mint. 

#### Where does it add cost?
Seems like it has more logic and code and deployer has to spend additional gas during deployment.