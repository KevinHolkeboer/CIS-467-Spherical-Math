```js
const phi = (1+Math.sqrt(5))/2;
const phim = -phi;
const phibar = (1-Math.sqrt(5))/2;
const phibarm = -phibar;
const cube = { {1, 1, 1},
{ 1, 1, -1},
{ 1, -1, 1 },
{ 1, -1, -1 },
{ -1, 1, 1 },
{ -1, 1, -1 },
{ -1, -1, 1 },
{ -1, -1, -1 } };

const cubefaces =
{ {1, 0, 2, 3},
{4, 5, 7, 6},
{0, 1, 5, 4},
{3, 2, 6, 7},
{2, 0, 4, 6},
{1, 3, 7, 5}};

const dodecahedron =
{ { 1,1,1 },
{ 1,1,-1},
{ 1,-1, 1},
{ 1,-1, -1},
{ -1, 1, 1 },
{ -1, 1, -1 },
{ -1, -1, 1 },
{ -1, -1, -1 },
{ phibarm, phi, 0 },
{ phibar, phi, 0 },
{ phibarm, phim, 0 },
{ phibar, phim, 0 },
{ phi, 0, phibarm },
{ phi, 0, phibar },
{ phim, 0, phibarm },
{ phim, 0, phibar },
{ 0, phibarm, phi },
{ 0, phibar, phi },
{ 0, phibarm, phim },
{ 0, phibar, phim } };

const dodecfaces =
{ { 1, 8, 0, 12, 13 },
{ 4, 9, 5, 15, 14 },
{ 2, 10, 3, 13, 12 },
{ 7, 11, 6, 14, 15 },
{ 2, 12, 0, 16, 17 },
{ 1, 13, 3, 19, 18 },
{ 4, 14, 6, 17, 16 },
{ 7, 15, 5, 18, 19 },
{ 4, 16, 0, 8, 9 },
{ 2, 17, 6, 11, 10 },
{ 1, 18, 5, 9, 8 },
{ 7, 19, 3, 10, 11 } };

const octahedron =
{ { 1, 0, 0 },
{ -1, 0, 0 },
{ 0, 1, 0 },
{ 0, -1, 0 },
{ 0, 0, 1 },
{ 0, 0, -1} };

const octfaces =
{ { 0, 2, 4},
{ 2, 0, 5 },
{ 3, 0, 4 },
{ 0, 3, 5 },
{ 2, 1, 4 },
{ 1, 2, 5 },
{ 1, 3, 4 },
{ 3, 1, 5 } };

const tetrahedron =
{ { 1, 1, 1 },
{ 1, -1, -1 },
{ -1, 1, -1 },
{ -1, -1, 1 } };

const tetfaces =
{ { 3, 2, 1},
{ 2, 3, 0 },
{ 1, 0, 3 },
{ 0, 1, 2 } };

const icosahedron =
{ { phi, 1, 0 },
{ phim, 1, 0 },
{ phi, -1, 0 },
{ phim, -1, 0 },
{ 1, 0, phi },
{ 1, 0, phim },
{-1, 0, phi },
{-1, 0, phim },
{0, phi, 1 },
{0, phim, 1},
{0, phi, -1 },
{0, phim, -1} };

const icosfaces =
{ { 0, 8, 4 },
{ 0, 5, 10 },
{ 2, 4, 9 },
{ 2, 11, 5 },
{ 1, 6, 8 },
{ 1, 10, 7 },
{ 3, 9, 6 },
{ 3, 7, 11 },
{ 0, 10, 8 },
{ 1, 8, 10 },
{ 2, 9, 11 },
{ 3, 11, 9 },
{ 4, 2, 0 },
{ 5, 0, 2 },
{ 6, 1, 3 },
{ 7, 3, 1 },
{ 8, 6, 4 },
{ 9, 4, 6 },
{ 10, 5, 7 },
{ 11, 7, 5 } };
```
