


\``typescript
interface Book {
  author: string;
  coverPhotoURL: string;
  readingLevel: string;
  title: string;
}

const getRandomBooks = (books: Book[], count: number): Book[] => {
  const shuffled = [...books].sort(() => 0.5 - Math.random());
  return shuffled.slice(0, count);
};
\``
