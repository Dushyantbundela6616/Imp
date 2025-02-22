# Imp
Book store
import React from "react"; impor
t { BrowserRouter as Router, Route, Routes } from "react-router-dom"; import { Navbar, Footer, BookList, BookDetail, Cart, Checkout } from "./components";

const App = () => { return ( <Router> <Navbar /> <Routes> <Route path="/" element={<BookList />} /> <Route path="/book/:id" element={<BookDetail />} /> <Route path="/cart" element={<Cart />} /> <Route path="/checkout" element={<Checkout />} /> </Routes> <Footer /> </Router> ); };

export default App;


